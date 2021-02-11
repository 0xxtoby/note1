# Driftnet学习笔记

## 一、工具介绍

- driftnet是一款简单而使用的图片捕获工具，可以很方便的在网络数据包中抓取图片。

- 这次用到这个工具的原因是与 ettercap 相配合，抓去被害人浏览的图片。

- 此篇应与 ettercap ARP欺骗相互配合观看。


#### 命令介绍

#### 命令原型

``` cmd
driftnet  [options]  [filter code] 
```

·     

**参数命令**

> ` -b ` ：捕获到新的图片时发出嘟嘟声
>
> ` -i interface` ：选择监听接口
>
> `-f file `：读取一个指定pcap数据包中的图片
>
> ` -p` ：不让所监听的接口使用混杂模式
>
> ` -a` ：后台模式：将捕获的图片保存到目录中（不会显示在屏幕上）
>
> ` -m number` ：指定保存图片数的数目
>
>  `-d directory` ：指定保存图片的路径
>
>  `-x prefix `：指定保存图片的前缀名

#### 命令示例

``` cmd
# driftnet -i eth0 -d /root/ 

/*

   因为我们是配合ettercap 进行ARP欺骗，所以所有的被害者流量都会从

  我方端口经过（有线），所以端口为eth0.

*/
```



 

## 二、Ettercap 进行ARP欺骗 实验笔记

### 实验需求

- ​    攻击机与被攻击机位于同一局域网内

- ​    此实验中，攻击机为 Kali Linux

- ​    被攻击机为 苹果手机 与 Win7虚拟机


### 实验步骤

##### 打开 Ettercap

>  Ettercap 支持*命令行*与*图形界面* 双模式，但其图形界面很优美，故我们选用图形界面。

``` cmd
# ettercap -G 

 /* 该命令打开 Ettercap 的（GTK+ GUI）*/
```



##### 确定监听网卡

- 选择 Sniff —- Unified-sniffing ，然后选择网卡。 

- 
  在这里，我们用有线攻击局域网内目标。故选择 eth0。

- 当然我们还可以，点击下拉箭头，打开网卡备选。

- 点击确定。




##### 扫描局域网内全部主机

​	 Hosts — Scan for hosts — Hosts list。这时，就可以看到局域网内所有的主机。



##### 选定目标

> - 在列表里面，选定目标主机，然后点add to target 1,将目标主机添加到目标1;
>
> - 在列表里面，选定路由，点add to target 2,将路由添加到目标2： 
>
> - 
>   PS.路由就是我们的网关，可以用 ifconfig 来查看。
>



##### 选择攻击方式

> 然后点 mitm — arp posoning ，勾选 sniff remote connections：



##### 开始攻击

> 点击start — start sniffing开始监听。



##### 密码解析

> 其中如果被劫持的主机访问一些比较明显的用户名和密码，Ettercap就会自己显现在屏幕上。但是，现在的网络环境下，很少是明文传输。很多都是MD5加密。可以在线破解。

#### 拓展

##### 获取图片流

> 我们用 driftnet 工具。

```
driftnet -i eth0 -d /root/ 
```





 





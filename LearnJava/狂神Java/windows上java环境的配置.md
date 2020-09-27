# windows环境下Java编程环境的配置

## 安装jdk

由于国内的网络环境，无法正常获取oracle的jdk，可以去华为的镜像下载

```
https://repo.huaweicloud.com/java/jdk/
```

我在这里下载了8u202的版本，就是下载`jdk-8u202-windows-x64.exe`

下载好之后安装，一路默认下一步即可

## 配置环境变量

环境变量首先需要增加`JAVA_HOME`变量，设置为jdk的路径，我的路径为`C:\Program Files\Java\jdk-13.0.2`

然后需要在```PATH```环境变量中添加```%JAVA_HOME%\bin```和```%JAVA_HOME%\jre\bin``` 

完成之后打开一个cmd窗口，输入```java -version```，看见正常的版本输出说明配置正常

## IDEA的安装

idea是一个Java开发的IDE，[下载地址](https://www.jetbrains.com/idea/)

下载好之后安装，一路默认即可。安装位置可以选择在SSD中，这样加载快一点。

最新版本2020.2的激活比较麻烦，激活方式见[网址](https://www.macenjoy.co/blog/jetbrains-2020)

## Java帮助文档离线版

百度搜索jdk api 1.8_google 








# Apache Server简介
Apache Server是一个为现代操作系统提供Http服务的安全、有效且灵活的HTTP服务器。  
Apache Server`(httpd)`起源于1995年，自从1996年成为了最受欢迎的Web服务器。

### 1. Apache的版本问题
目前推荐的可用的发布版是1.3、2.0和2.2，下载请参考[archive download site](https://archive.apache.org/dist/httpd/)  
最新的稳定版本：[2.4.53](https://httpd.apache.org/download.cgi#apache24)

> Apache version > 2.2的版本将不会支持运行在早于Windows 2000的操作系统上

## 获取Apache Server
### 1. windows环境安装Apache Server
Apache Server为Windows操作系统提供了多种不同的[安装方式](https://httpd.apache.org/docs/current/platform/windows.html#down)，可以通过二进制编译来完成Apache Server的安装，但是这种方式需要准备各种依赖的环境，比较麻烦。另一方面，Apache提供了一系列的第三方供应商，用户可以根据不同的需求下载对应的软件包来进行安装。

1. [binary distribution](https://httpd.apache.org/docs/current/platform/win_compiling.html)  
2. [distributions]((https://httpd.apache.org/docs/current/platform/windows.html#down))

> 编译参考 1，安装第三方包参考 2


* 由于2.4.x版本是最新的版本，这里我使用官方推荐的可用版本：2.2版本  
* 由于没有build binary的需求，且我准备结合Php来学习Apache Server，所以我选择第三方的包：[Bitnami WAMP Stack](http://bitnami.com/stack/wamp)
* 关于`Binimi WAMP Stack Doc`的[Document](https://docs.bitnami.com/installer/infrastructure/wamp/)


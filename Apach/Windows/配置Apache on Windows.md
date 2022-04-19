# Apache Server配置
Apache Server的配置文件在`conf`子目录下，在Windows和Unix操作系统上的配置主要区别在于命令的稍微不同。
* 由于Apache Server在Windows上是多线程的，所以它不会像在Unix系统上为每一个request创建一个独立的进程。在Windows通常使用两个进程(父进程和子进程)：子进程用来处理请求，每个被子进程处理的请求将会独立创建一个线程来处理。
* 进程管理命令也不同：  
    a. `MaxConnectionsPerChild`: 
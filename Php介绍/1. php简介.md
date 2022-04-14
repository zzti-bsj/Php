# Php简介
Php全称Hypertext Preprocessor，意思是“超文本处理器”。Php是服务端脚本语言，能够嵌入到HTML，适用于多种Web应用的开发。  

## 简单示例
在脚本中使用`Php处理指令`嵌入到HTML内容中，执行Php的代码逻辑。
```php
<!DOCTYPE html>
<html>
    <head>
        <title>Example</title>
    </head>
    <body>
        <?php
            echo "Hi, I'm a PHP script!";
        ?>
    </body>
</html>
```

## 服务端脚本 & 客户端脚本
javaScript是客户端脚本语言；Php相比于JavaScript是服务端脚本语言。

服务端脚本语言在服务端执行代码，每次把执行的结果发送到客户端，客户端只能看到执行之后的HTML页面，看不到服务器脚本的内容；而客户端脚本语言，比如JavaScript，在浏览器端(Client)可以将数据存入浏览器的进程，这样下次就不用重新建立连接，可以从自己的主机上找到数据。

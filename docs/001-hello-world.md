# connect to local:
```shell
telnet 127.0.0.1 3000
```


## resouces:
+ https://blog.csdn.net/real_bird/article/details/52705640
+ https://www.jianshu.com/p/8df7a589cb0c


```shell
$telnet 127.0.0.1 3000
Trying 127.0.0.1...
Connected to localhost.
Escape character is '^]'.
GET / HTTP/1.1

HTTP/1.1 200 OK
Date: Thu, 30 Aug 2018 02:16:13 GMT
Connection: keep-alive
Transfer-Encoding: chunked

b
Hello world
0

Connection closed by foreign host.
```

## steps:
1. 连接 localhost:
```shell
telnet 127.0.0.1 3000
```
2. 输入：(输入完成之后，敲2次回车)
```
GET / HTTP/1.1
Connection: Keep-Alive
```

3. 返回：
```
HTTP/1.1 200 OK
Date: Thu, 30 Aug 2018 02:16:13 GMT
Connection: keep-alive
Transfer-Encoding: chunked

b
Hello world
0
```



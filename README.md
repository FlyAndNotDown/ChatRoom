<div align="center">
    <h1>ChatRoom CLI</h1>
    <h6>一个 Python Socket 实现的纯命令行聊天室</h6>
</div>

# 预览

![Preview](./doc/preview.gif)

# 运行前要求

* `python` 版本 `3+`

# 运行方法

进入项目根目录，执行命令：

```shell
python3 ./server_start.py
```

来启动服务器

执行命令：

```shell
python3 ./client_start.py
```

来启动客户端

# 客户端命令

运行之后，你可以在客户端输入命令来使用聊天室功能，输入：

```shell
help
```

可以获取帮助，输入：

```shell
login ${nickname}
```

可以以 `${nickname}` 作为用户名登录，输入：

```shell
send ${message}
```

可以发送消息 `${message}` 给聊天室登录的所有用户

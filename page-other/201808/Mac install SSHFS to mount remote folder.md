# 安装SSHFUS
sshfs依赖于fuse，所以需要先安装fuse，这两个软件都可以在[https://osxfuse.github.io](https://osxfuse.github.io)下载到。

注意安装顺序。

# 挂载文件夹到本地
输入一下命令：
```shell
sshfs jerryqi@8.8.8.8:/var/www/html /Users/jerryqi/Desktop/Library-Stage
```
我使用的是公钥登陆
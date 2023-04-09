# FTP工具-仿终端操作版

基于TCP协议使用Python开发的FTP管理工具，比较简陋，可以拓展功能，能使用一些简单的命令

比较简陋，路径请尽量以绝对路径为准（部分地方支持相对路径），测试平台为`Linux Mint`

注意权限问题；文件名尽量不含空格，不然某些命令会报错

命令大全：

- cd - 在服务器上切换路径，切换上一次的所在路径，而非上一级路径
- cd home 在服务器上中从根区切换到下一级子目录home目录
- cd /home 同上
- ls 当前路径下的所有文件以及文件夹
- mkdir 文件夹路径\n 创建相对应的文件夹
- rm 路径 危险指令，删除当前路径对应的的文件或者文件夹（包括非空文件夹）
- dl 服务器文件名 本地文件路径\n 将所在路径下的服务器文件下载到本地文件，本地文件可被创建，请确保本地文件所处文件夹存在
- up 本地文件路径 服务器文件名\n 将本地文件上传到所在服务器的路径下，服务器文件可被创建
- quit 退出客户端
- exit 同上

# 使用方法

1. 将server挂在服务端，运行

2. 将client中的ip地址更换成服务端的ip地址，运行即可

如若出现端口被占用，更换端口即可

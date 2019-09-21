# 常用的Docker命令
## 查看当前的仓库
```
docker images
```
## 远程下载镜像
```
dockeer pull 镜像名称
```
## 构建镜像(.代表当前目录)
```
docker build .
```
## 构建镜像加命名镜像(.代表当前目录)
```
docker build -t 名称:版本 .
```
## 运行
```
docker run -d -p 80(Linux上的关联端口):8080(docker上Tomcat端口) 镜像名称
```
## 查看docker进程
```
docker ps
```
## 关闭
```
docker stop 容器进程
```
## 重启容器
```
docker restart 加docker进程
```
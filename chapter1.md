# 镜像
---
## 简介
- 镜像是一个Docker的可执行文件，其中包括运行应用程序所需的所有代码内容、依赖库、环境变量和配置文件等。
- 通过镜像可以创建一个或多个容器。

## 管理


|command|option|
|-|-|
|`docker search`||
|`docker images/docker image ls`||
|`docker pull`||
|`docker rmi/docker image rm`||
|`docker save`||
|`docker load`||
|`docker tag`<br>对本地镜像的NAME、TAG进行重命名，并新产生一个命名后镜像<br>`docker tag SOURCE_IMAGE[:TAG] TARGET_IMAGE[:TAG]`|无|
|`docker inspect/docker image inspect`<br>查看本地一个或多个镜像的详细信息<br>`docker image inspect [OPTIONS] IMAGE [IMAGE...]`<br>或者 `docker inspect [OPTIONS] IMAGE [IMAGE...]`|`-f, --format string          利用特定Go语言的format格式输出结果`|
|`docker history`<br>查看本地一个镜像的历史(历史分层)信息<br>docker history [OPTIONS] IMAGE|`-H, --human		将创建时间、大小进行优化打印(默认为true)` <br>`-q, --quiet           	只显示镜像ID` <br>`--no-trunc        	不缩略显示`|










## 总结


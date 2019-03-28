# 镜像
---
## 简介
- 镜像是一个Docker的可执行文件，其中包括运行应用程序所需的所有代码内容、依赖库、环境变量和配置文件等。
- 通过镜像可以创建一个或多个容器。

## 管理


|command|option|
|-|-|
|`docker search`<br>搜索Docker Hub(镜像仓库)上的镜像<br>`docker search [OPTIONS] TERM`|`-f,  --filter filter   	根据提供的格式筛选结果`<br>`--format string   	利用Go语言的format格式化输出结果`<br>`--limit int       	展示最大的结果数，默认25个`<br>`--no-trunc        	内容全部显示`<br>|
|`docker images/docker image ls`<br>列出本地镜像<br>`docker images [OPTIONS] [REPOSITORY[:TAG]]`<br>或者`docker image ls [OPTIONS] [REPOSITORY[:TAG]]`|`-a, --all             	展示所有镜像 (默认隐藏底层的镜像)`<br>
`--no-trunc        	不缩略显示`<br>
`-q, --quiet           	只显示镜像ID`|
|`docker pull`||
|`docker rmi/docker image rm`||
|`docker save`||
|`docker load`||
|`docker tag`<br>对本地镜像的NAME、TAG进行重命名，并新产生一个命名后镜像<br>`docker tag SOURCE_IMAGE[:TAG] TARGET_IMAGE[:TAG]`|无|
|`docker inspect/docker image inspect`<br>查看本地一个或多个镜像的详细信息<br>`docker image inspect [OPTIONS] IMAGE [IMAGE...]`<br>或者 `docker inspect [OPTIONS] IMAGE [IMAGE...]`|`-f, --format string          利用特定Go语言的format格式输出结果`|
|`docker history`<br>查看本地一个镜像的历史(历史分层)信息<br>docker history [OPTIONS] IMAGE|`-H, --human		将创建时间、大小进行优化打印(默认为true)` <br>`-q, --quiet           	只显示镜像ID` <br>`--no-trunc        	不缩略显示`|










## 总结


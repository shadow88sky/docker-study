# docker-study
## docker基本命令
+ docker info & docker version 

> docker info命令用于检查docker是否正确安装，如果正确安装，该命令会输出docker的配置信息  
docker info命令一般结合docker version命令使用，两者结合使用能够提取到足够详细的docker环境信息。  

+ docker run  

> docker run命令使用方法如下:  
docker run[OPTIONS] IMAGE [COMMAND][ATG...]  
docker run命令是docker的核心命令之一，用来基于特定的镜像创建一个容器，并依据选项来控制该容器。  

+ docker start/stop/restart命令  

> docker run命令可以新建一个容器来运行，而对于已经存在的容器，可以通过docker start/stop/restart命令来启动，停止和重启。  

+ docker images命令  

> 通过docker images命令可以列出主机上的镜像，默认只列出最顶层的镜像，可以使用-a选项显示所有镜像。  

+ docker rmi 和 docker rm命令  

> 这两个子命令的功能都是删除，docker rmi命令用于删除镜像，docker rm命令用于删除容器。它们可以同时删除多个镜像或容器，也可以按条件来删除。  
  需要注意的是，使用rmi命令删除镜像时，如果已有基于该镜像启动的容器存在，则无法直接删除，需要首先删除容器。  
  
+ docker attach命令  
> 它可以链接到正在运行的容器，观察该容器的运行情况，或与容器的主进程进行交互。

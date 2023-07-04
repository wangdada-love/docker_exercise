# docker_exercise
note of docker learn

# 简介
  vmware需要创建完整的操作系统，docker不需要。
  dotCloud公司开发
  使用golang语言开发
  基于Linux内核的Cgroups、Namespace以及Union FS等技术。
  * 作用：对操作系统进行隔离，
# docker引擎
  C/S架构
  docker客户端命令行 - API接口 - 服务器端docker进程（Server Docker Daemon）
  可对网络、容器、镜像、数据卷进行管理。
  ## Docker Daemon
  安装使用docker，需要先运行docker daemon进程，用于管理docker
  ## Docker Client
  客户端使用REST API 和 Docker Daemon 进行访问

  ## Docker平台组成

  包含以下三部分：
  
    *客户端
        Docker的构建、拉取和启动
    *Docker主机
        包括服务器、容器、镜像
    *镜像仓库

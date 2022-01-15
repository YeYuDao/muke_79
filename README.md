# muke_79
SpringCloud+Kubernetes 微服务容器化交付实战
SpringCloud+Kubernetes 微服务容器化交付实战
👇👇👇👇👇👇👇👇点击图片跳转下载地址👇👇👇👇👇👇👇
### 第1章 课程导学 

#### 本章主要介绍为何要带大家学习微服务的容器化持续交付实战课程，之后会为大家介绍本课程内容具体安排，最后给出如何学好这门课程的一些学习建议。希望大家都能通过这门课程，学有所成，学有所归。
1-1 课前必读（不看会错过一个亿）

1-2 课程介绍及学习指导 (06:24)


### 第2章 持续交付方法 

#### 本章将会介绍持续交付的定义和互联网公司里持续交付流水线方法和模型，为后面的实践课程建立理论基础。
2-1 互联网公司如何进行持续集成【理论支撑】 (11:11)

2-2 互联网公司如何进行持续部署【理论支撑】 (11:30)


### 第3章 从需求开始

#### 本章带你从项目经理视角，看需求如何管理，需求和代码如何溯源，开发工具和 Jira 需求管理工具如何集成，从而建立需求管理和代码提交的最佳实践。
3-1 Docker安装Jira (06:56)

3-2 使用Jira创建Sprint、用户故事和任务 (09:05)

3-3 在Jira看板里进行任务分配和排期 (05:32)

3-4 在Idea里安装Jira插件，自动在本地创建分支 (06:32)

3-5 Gitflow VS Trunk base分支模型哪个更适合您的团队 (06:24)


### 第4章 开发Spring Cloud应用：Notebook

#### 本章是课程的核心章节，将通过编基于写Spring Cloud 2.1.4版本的Notebook应用来体现微服务和传统 SpringMVC 应用的区别，包括 Spring Cloud注册中心Eureka，负载均衡Zuul，服务治理Zipkin等一系列组件。
4-1 开发一个Spring Boot应用：Notebook-1.0.jar (24:36)

4-2 创建 Spring Cloud服务注册中心 (09:54)

4-3 在Notebook应用前端加上网关 (11:31)

4-4 服务链路追踪Zipkin (09:05)


### 第5章 微服务应用打包 

#### 本章将带大家学习如何使用 Maven进行多模块应用的打包，并且将制品发布到开源制品库 Artifactory。
5-1 Apache Maven核心 (12:23)

5-2 搭建Maven私服 (11:48)

5-3 从Maven私服下载制品 (11:09)


### 第6章 Jenkins: 为 NoteBook 搭建流水线

#### 本章基于 Jenkins核心通过 Jenkins 的流水线，集成应用的单元测试JUnit，静态代码检查 Sonarqube，接口自动化测试 YAPI，UI 自动化测试 Selenium，将各个测试工具串联在持续集成流水线中，提升软件交付的质量。
6-1 Jenkins核心 (15:38)

6-2 Jenkins持续集成流水线 (10:28)

6-3 Jenkins集成Artifactory (13:01)

6-4 Jenkins集成Jira (08:31)

6-5 Jenkins集成Sonarqube代码扫描 (08:25)

6-6 Jenkins集成YAPI (07:03)

6-7 Selenium集成 (06:40)


### 第7章 为应用编写多维度测试用例

#### 本章将介绍如何为应用编写单元测试用例，如何执行静态代码检查，编写接口自动化测试用例，编写UI 自动化测试用例，对应用进行全面的测试。
7-1 为Notebook应用增加单元测试 (06:07)

7-2 用Sonarcube检查Notebook的代码是否规范 (05:45)

7-3 使用YAPI为应用增加Notebook接口测试用例 (04:20)

7-4 使用Selenium执行Notebook UI自动化测试 (07:44)


### 第8章 使用Ansible Playbook部署微服务

#### 本章将带大家完成Ansible的安装和配置，编写第一个Ansible脚本，带大家了解Ansible Playbook的最佳实践， 并为Notebook微服务编写Ansible Playbook，最后在流水线中集成Notebook的Playbook。
8-1 Ansible核心 (10:13)

8-2 Ansible安装配置 (10:56)

8-3 编写第一个Ansible命令 (12:25)

8-4 Ansible Playbook介绍 (08:43)

8-5 可复用的Playbook (12:30)

8-6 为Notebook编写Playbook (09:31)

8-7 流水线中集成Ansible Playbook进行部署 (06:37)

8-8 Ansible Playbook最佳实践 (14:09)


### 第9章 深入理解Docker 原理，实战容器化发布Notebook应用

#### 本章是课程的核心章节，会详细阐述 Docker 底层的实现原理，帮您深入理解 Docker 的进程，资源，文件系统的实现原理，并且会搭建免费 Docker 镜像仓库，实现一个 Notebook 应用的 Docker 镜像，并将镜像发布到 Docker 镜像仓库。
9-1 为什么互联网公司都在用Docker替代虚拟机 (07:43)

9-2 Docker是如何实现资源隔离的 (09:41)

9-3 Docker是如何实现进程空间隔离的 (06:30)

9-4 Docker是如何实现存储隔离的 (08:18)

9-5 Docker镜像的常用命令 (07:21)

9-6 搭建免费版Docker镜像仓库 (10:54)

9-7 开始编写Notebook的Dockerfile (10:20)

9-8 Dockerfile最佳实践 (08:54)

9-9 构建微服务的Docker镜像并上传镜像 (06:18)

9-10 使用Docker运行多个微服务 (12:21)


### 第10章 将Notebook Docker镜像部署到Kubernetes

#### 本章是课程的核心章节，会详细阐述 Kubernetes 的核心概念，包括 Pod，Deployment，Service, PV，秘钥，configmap，探针，Helm Chart 打包等等，并且包含使用的最佳实践，最后会为 Notebook创建一键部署的 Helm Chart。
10-1 minikube (17:53)

10-2 namespace (09:39)

10-3 Kubernetes pod (11:39)

10-4 Kubernetes service (13:28)

10-5 Kubernete的存储 (16:55)

10-6 Kubernete deployment (15:31)

10-7 Kubernetes探针的作用 (08:45)

10-8 Kubernetes configmap (09:30)

10-9 Kubernetes部署notebook多个微服务 (15:06)

10-10 Kubernetes的日志系统 (11:43)

10-11 Kubernetes的秘钥管理 (10:02)

10-12 helm入门 (10:51)

10-13 为notebook服务创建helmchart (15:10)

10-14 使用helm进行应用的升级和回滚 (07:50)


### 第11章 微服务容器化持续交付实操

#### 本章将通过实操的方式，把前面代码关联需求，自动化测试，持续集成流水线，容器镜像的晋级，Helm Chart在 Kubernetes 环境里一键部署。通过实践的方式深刻理解持续交付的魅力。
11-1 编写Notebook应用新功能关联Jira需求并运行在本地测试环境 (09:57)

11-2 在Jenkins流水线进行打包代码扫描镜像构建 (09:36)

11-3 在Jenkins里将该镜像上传到JCR并部署到Kubernetes的测试环境空间 (07:36)

11-4 Jenkins触发接口自动化测试 (09:04)

11-5 在Jenkins中对该Docker镜像晋级到Prod仓库 (07:28)

11-6 在Jenkins里将该镜像部署到Kubernetes的生产环境空间 (07:49)


[下载地址](https://51xueit.vip "下载地址")

# kubernetes-windows-node-toolset
Windows GUI Toolset for deploying Kubernetes Windows worker nodes

Kubernetes Windows Node Toolset提供图形的操作界面，可以方便快速地把Windows Server 2019加入Kubernetes集群。

主要功能包括：

	初始化服务器 （设置主机名、关闭防火墙与杀毒软件、启用远程桌面、关闭自动更新、安装监控插件、设置NTP对时服务）

	安装与设置Docker参数

	安装Kubernetes组件并将其加入Kubernetes集群

	修改核心服务参数（Kubelet、KubeProxy、Flannel）

	获取Kubernetes集群节点信息

	在线获取本工具在离线环境部署节点时需要的所有资源包

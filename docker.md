## history
1979 chroot Jail    
2007 Process Containers(Cgroups)   
2008 LXC(Linux Containers) , Linux kernel 2.6.24  
2013 Docker

## key technology
### Namespace
环境隔离，全局资源封装
### Cgroups
资源控制，限制和隔离一组进程对系统资源的使用
### rootfs
文件系统，挂载容器根目录
### Union FS  
分层，镜像叠加


## Docker Arch
### client
docker pull/build/run 
### Host
docker daemon (manage image,network,volume)
### Registry

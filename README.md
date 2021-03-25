# dd


DD脚本备份


## Debian/Ubuntu:
```
apt-get update
apt-get install -y xz-utils openssl gawk file
```
## RedHat/CentOS:
```
yum update
yum install -y xz openssl gawk file
```

## 全自动安装Ubuntu 16.04 x64： 
```
bash InstallNET.sh -u 16.04 -v 64 -a
```

## 全自动安装Debian 9 x64：
```
bash InstallNET.sh -d 9 -v 64 -a
```

## 全自动安装Debian 10 x64(中科大镜像源，用于国内服务器)： 
```
bash InstallNET.sh -d 10 -v 64 -a --mirror 'http://mirrors.ustc.edu.cn/debian/'
```

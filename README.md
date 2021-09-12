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

## 全自动安装Ubuntu 20.04 x64： 
```
bash newNet.sh -u 20.04 -v 64 -a
```

## 全自动安装Debian 11 x64：
```
bash newNet.sh -d 11 -v 64 -a
```

## 全自动安装Debian 11 x64(中科大镜像源，用于国内服务器)： 
```
bash newNet.sh -d 11 -v 64 -a --mirror 'http://mirrors.ustc.edu.cn/debian/'
```

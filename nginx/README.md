# 命令

## nginx.conf 配置验证
nginx -t

## windows刷新
nginx -s reload

## nginx服务是否运行
tasklist | findstr nginx

## 终止所有进程
taskkill /IM nginx.exe /f

## 启动
start nginx

## 机器名称
hostname

## 操作系统
cat /etc/redhat-release

## CPU
lscpu | proc/cpuinfo | grep processor | wc -l

## 内存
free -m

## 磁盘
df -h

## 外网ip
curl cip.cc  | nslookup 域名

## Ng配置地址
ps -ef|grep nginx

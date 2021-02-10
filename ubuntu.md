# Ubuntu

## ifconfig 没有内网地址
sudo dhclient ens33

## 下载资源死锁
Could not get lock /var/lib/dpkg/lock-frontend - open (11: Resource temporarly unavailable)
solution:
> sudo rm /var/lib/dpkg/lock-frontend   
> sudo rm /var/lib/dpkg/lock

## 修改Ubuntu字体大小
综合调节 system settings中apperence的侧边栏大小和display的比例
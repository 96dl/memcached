# memcached builds for Windows

##计划任务设置方法
schtasks /create /sc onstart /tn memcached /tr "'D:\memcached\memcached-1.5.1.exe' -m 512"

##计划任务卸载方法
schtasks /delete /tn memcached

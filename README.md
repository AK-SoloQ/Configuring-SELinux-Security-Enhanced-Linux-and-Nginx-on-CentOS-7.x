# Configuring-SELinux-Security-Enhanced-Linux-and-Nginx-on-CentOS-7.x

> # setsebool -P httpd_can_network_connect on
> # setsebool -P httpd_enable_homedirs on
> # chcon -R -t  httpd_sys_content_t  /home/user/folder

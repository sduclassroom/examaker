Display the current SELinux mode?

+ `[root@serverX ~]# getenforce`

* `[root@serverX ~]# selinux`
+ `[root@serverX ~]# grep '^SELINUX' /etc/selinux/config`
+ `[root@serverX ~]# setenforce`
+ `[root@serverX ~]# semanage fcontext -l`

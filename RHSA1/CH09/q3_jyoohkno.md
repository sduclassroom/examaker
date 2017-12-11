The sshd service has to be restarted to put the changes into effect:
  +[root@serverX ~]# systemctl restart sshd
  *[student@desktopX ~]$ lab ssh setup
  *[student@desktopX ~]$ ssh student@serverX
  *[student@desktopX ~]$ ssh visitor@serverX
  *[student@host ~]$ restart file

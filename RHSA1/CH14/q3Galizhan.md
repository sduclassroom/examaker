Create a hard link newfile-link2.txtfor the existing file newfile.txt in the /tmp directory

+ [root@serverX ~]# cat newfile.txt /tmp/newfile-hlink2.txt
* [root@serverX ~]# rm newfile.txt /tmp/newfile-hlink2.txt
* [root@serverX ~]# ls -l newfile.txt /tmp/newfile-hlink2.txt
* [root@serverX ~]# ln newfile.txt /tmp/newfile-hlink2.txt

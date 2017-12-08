Which of this commands are mounting by device file of the partion that hold in

+ [root@serverX ~]# mount /dev/vbd1 /mnt/mydata
* [root@serverX ~]# mount UUID="46f543fd-78c9-4526-a857-244811be2d88" /mnt/mydata
* [root@serverX ~]# mount /dev/vbd1 /mnt/mydata
* [root@serverX ~]# lsof /dev/vbd1 /mnt/mydata

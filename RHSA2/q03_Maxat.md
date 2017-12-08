How to To add or modify the other ACL?
+ `[student@serverX ~]$ setfacl -m o::- file`				
* `[student@serverX ~]$ setfacl -s p::- file`
* `[student@serverX ~]$ setfacl -n o::- file`
* `[student@serverX ~]$ setfacl -x p::- file`
* `[student@serverX ~]$ setfacl -i s::- file`

How can To add or modify a group or named group ACL?
* `[student@serverX ~]$ setfacl -s g:name:rw file`
+ `[student@serverX ~]$ setfacl -m g:name:rw file`
* `[student@serverX ~]$ setfacl -t g:name:rw file`
* `[student@serverX ~]$ setfacl -r g:name:rw file`

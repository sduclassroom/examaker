How to Add multiple entries via the same command, and comma-separate each of the entries?
+ `[student@serverX ~]$ setfacl -m u::rwx,g:sodor:rX,o::- file`
* `[student@serverX ~]$ setfacl -m u::rwx,g:rX,o::- file`
* `[student@serverX ~]$ setfacl -m u::rwx,g:sodor:- file`
* `[student@serverX ~]$ setfacl -m u::rwx,g:sodor:rX,o:`
* `[student@serverX ~]$ setfacl -m :sodor:rX,o::- file`

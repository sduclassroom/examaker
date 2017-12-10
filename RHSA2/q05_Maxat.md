 How to delete a default ACL is also the same as deleting a standard ACL; again, preface with d:, or use the -d option?
* `[student@serverX ~]$ setfacl -x d:name directory`
+ `[student@serverX ~]$ setfacl -x d:u:name directory`
* `[student@serverX ~]$  -x d:u:name directory`
* `[student@serverX ~]$ setfacl :name directory`
* `[student@serverX ~]$ setfacl -x d:directory`

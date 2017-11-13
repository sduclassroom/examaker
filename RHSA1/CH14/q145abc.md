List all files in the  **/usr/bin** directory with a file size greater than __50__ kilobytes?

* `[root@serverX ~ ]# find /home/student -nmin +50k`
+ `[root@serverX ~ ]# find /usr/bin -size +50k`
* `[root@serverX ~ ]# find /tmp nmin -50k`
* `[root@serverX ~ ]# find /usr/bin -size -50k`

Commmand to set the SELinux context for the files in /var/web-content

+ `restorecon -R /var/web-content/`

* `setstorecon -R /var/web-content`
* `semanage /var/web-content`
* `sealert -l /var/web-content`
* `semanage fcontext /var/web-content`

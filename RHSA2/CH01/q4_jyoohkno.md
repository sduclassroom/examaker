Allows the graphical installation to be viewed remotely via VNC:
+ vnc --password=redhat
* repo --name="Custom Packages"
* url --url="ftp://installserver.example.com/pub/RHEL7/dvd"
* clearpart --all --drives=sda,sdb --initlabel
* vnc-- all

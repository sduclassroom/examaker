Which command changes the zone's interface  to `interface1` and bound it to zone `public`. 

* `sudo firewall-cmd --permanent --zone=public --adjust-interface=interface1`
* `sudo firewall-cmd --permanent --zone=public --add-interface=interface1`
+ `sudo firewall-cmd --zone=public --change-interface=interface1`
* `sudo firewall-cmd --permanent --zone=public --query-interface=interface1`
* `sudo firewall-cmd --zone=public --set-interface=interface1`

Append an entry to the file to specify the IPv4 address.

    echo "IPADDR1=10.0.X.1" >> /etc/sysconfig/network-scripts/ifcfg-eth0

    echo "PREFIX1=24" >> /etc/sysconfig/network-scripts/ifcfg-eth0

    nmcli con up "System eth0"

    echo "PREFIX1=24" >> /etc/sysconfig/

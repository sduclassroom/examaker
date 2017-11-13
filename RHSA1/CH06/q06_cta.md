Users and their groups:
```
lucy lucy,ricardo
ricky ricky,ricardo
ethel ethel,mertz
fred fred,mertz
```
There is permissions for files below, who can change the contents of lfile1
```
-rw-rw-r-- lucy   lucy    lfile1
-rw-r--rw- lucy   ricardo lfile2
-rw-rw-r-- ricky  ricardo rfile1
-rw-r----- ricky  ricardo rfile2
```

*`ricky and ethel`

*`only fred`

+`only lucy`

*`lucy and fred`

*`fred and ricky`

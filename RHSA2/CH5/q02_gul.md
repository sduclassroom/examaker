The number of cores using /proc/cpuinfo:

* `NCORES*2=$ (grep -c '^processor' /proc/cpuinfo )`
+ `NCORES=$ (grep -c '^processor' /proc/cpuinfo )`
* `NCORES=$ ((grep -c '^processor' /proc/cpuinfo ))`
* `NCORES*2-1=$ (grep -c '^processor' /proc/cpuinfo )`
* `NCORES-1=$ (grep -c '^processor' /proc/cpuinfo )`

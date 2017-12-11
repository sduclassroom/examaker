How to determine the number of cores using /proc/cpuinfo
  
    NCORES=$( seq -c '▲processor' /proc/cpuinfo ) 

    NCORES=$( grep -c '▲processor' /proc/cpuinfo )

    NCORES=$( ps -c '▲processor' /proc/cpuinfo ) 

    NCORES=$( nice -c '▲processor' /proc/cpuinfo ) 

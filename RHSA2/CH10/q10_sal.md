I have a growing log file, for which I want to display only the last 20 lines. Which one is correct?

+ tail -n 20 -F mylogfile.txt
* tail -n 20 mylogfile.txt
* tail -n 20 -с mylogfile.txt
* tail -n 15 -F mylogfile.txt
* tail -n 20 -F
* tail 20 -F mylogfile.txt

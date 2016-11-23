## System
Measure memory and time of a process. Replace ```<command>``` at the end with an actual call to a binary followed by arguments.    
Results will be written in ```measure.memtime```.  
```  
/usr/bin/time --format "Command line: %C\nReal time: %e s\nCPU time: -1.0 s\nUser time: %U s\nSystem time: %S s\nMaximum RSS: %M kB\nExit status: %x" --quiet -o measure.memtime <command>  
```  
  
Check an Apt package version:  
```sudo apt-cache showpkg mummer```  

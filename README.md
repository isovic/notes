### notes
Log of useful commands, tips and tricks.

## System
Measure memory and time of a process. Call the binary and corresponding arbuments instead of <command> at the end.  
Results will be written in ```measure.memtime```.  
```  
/usr/bin/time --format "Command line: %C\nReal time: %e s\nCPU time: -1.0 s\nUser time: %U s\nSystem time: %S s\nMaximum RSS: %M kB\nExit status: %x" --quiet -o measure.memtime <command>  
```  

CPU Performance Analysis (Linux VM)
top -1  correlated with jstack snapshots. 
See KCS article:  How do I identify high CPU utilization by Java threads on Linux/Solaris
Take snapshots during 3 minutes
Check files high-cpu.out and high-cpu-tdump.out to check on which threads CPU is spent

Usage: ./collect.sh PIDJAVAPROCESS

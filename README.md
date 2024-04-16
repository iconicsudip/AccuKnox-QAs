# System health monitor - 
This is a python script called `system_health.py` which helps to know the system health of any system and based on **THRESHOLD** it will give messages

## Explaination of code:
There is a class called `SystemHealth` which containes 6 methods which are explained below.
1. `get_all_usage` : Which will return CPU, Memory and Disk usages in percetage.
2. `get_all_stats` : Which will help user to know about the usages of CPU, Memory, Disk and Number of processes are running in the system.
3. `get_cpu_usage` : Which will help to know CPU usage, if usage is greater than CPU_THRESHOLD then it will show alert in console.
4. `get_memory_usage` : Which will help to know Memory usage, if usage is greater than MEMORY_THRESHOLD then it will show alert in console.
5. `get_disk_usage` : Which will help to know Disk usage, if usage is greater than DISK_THRESHOLD then it will show alert in console.
6. `get_running_processes` : Which will help to know number of processes are running in system.

**Note :** CPU_THRESHOLD, MEMORY_THRESHOLD, DISK_THRESHOLD are initially 80.

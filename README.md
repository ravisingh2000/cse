# cse2
practice 2
CPU schedules N processes which arrive at different time intervals and each process is allocated the CPU for a specific user
input time unit, processes are scheduled using a preemptive round robin scheduling algorithm. Each process must be assigned 
a numerical priority, with a higher number indicating a higher relative priority. In addition to the processes one task has priority 0. 
The length of a time quantum is T units, where T is the custom time considered as time quantum for processing. If a process is preempted 
by a higher-priority process, the preempted process is placed at the end of the queue. Design a scheduler so that the task with priority 0
does not starve for resources and gets the CPU at some time unit to execute. Also compute waiting time, turn around.

Answer: For solving that problem using round robin(time quantum )and priority .i use the concept of ageing also because in that problem 
the lower priority process will get  cpu at some unit of time so i increase the lower priority by some number so lower priority also get a 
cpu and reduce the waiting time of lower priority.

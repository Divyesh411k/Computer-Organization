# Computer-Organization
<h3>Process Managment</h3>
-><b>Preemptive Scheduling</b><br>
Preemptive scheduling is used when a process switches from the running state to the ready state or from the waiting state to the ready state.
Algorithms based on preemptive scheduling are Round Robin (RR), Shortest Remaining Time First (SRTF), Priority (preemptive version), etc. 

-><b>Non-Preemptive Scheduling</b><br>
Non-preemptive Scheduling is used when a process terminates, or a process switches from running to the waiting state.Algorithms based on non-preemptive scheduling are: Shortest Job First (SJF basically non preemptive) and Priority (nonpreemptive version), etc. 

<h3>Memory Allocation</h3>
<b>First Fit</b>
In the First Fit, the first available free hole fulfil the requirement of the process allocated. <br>

<b>Best Fit</b>
In the Best Fit, allocate the smallest hole that is big enough to process requirements. For this, we search the entire list, unless the list is ordered by size. <br>

<b>Worst Fit </b>
In the Worst Fit, allocate the largest available hole to process. This method produces the largest leftover hole. <br>

# Computer-Organization
<h3>Process Managment</h3>
->Preemptive Scheduling
Preemptive scheduling is used when a process switches from the running state to the ready state or from the waiting state to the ready state.
Algorithms based on preemptive scheduling are Round Robin (RR), Shortest Remaining Time First (SRTF), Priority (preemptive version), etc. 

->Non-Preemptive Scheduling
Non-preemptive Scheduling is used when a process terminates, or a process switches from running to the waiting state.Algorithms based on non-preemptive scheduling are: Shortest Job First (SJF basically non preemptive) and Priority (nonpreemptive version), etc. 

<h3>Memory Allocation</h3>
First Fit
In the First Fit, the first available free hole fulfil the requirement of the process allocated. 

Best Fit
In the Best Fit, allocate the smallest hole that is big enough to process requirements. For this, we search the entire list, unless the list is ordered by size. 

Worst Fit 
In the Worst Fit, allocate the largest available hole to process. This method produces the largest leftover hole. 

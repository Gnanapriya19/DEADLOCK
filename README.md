DEADLOCK AVOIDANCE 
AIM:
To Simulate Algorithm for Deadlock avoidance
DESCRIPTION:
In a multiprogramming environment, several processes may compete for a finite number of resources.
A process requests resources; if the resources are not available at that time, the process enters a waiting state.
Sometimes, a waiting process is never again able to change state,
because the resources it has requested are held by other waiting processes. This situation is called a deadlock.
Deadlock avoidance is one of the techniques for handling deadlocks. 
This approach requires that the operating system be given in advance additional information concerning which resources 
a process will request and use during its lifetime. With this additional knowledge, 
it can decide for each request whether or not the process should wait. To decide whether the current request can be 
satisfied or must be delayed, the system must consider the resources currently available, the resources currently 
allocated to each process, and the future requests and releases of each process. Banker’s algorithm is a deadlock 
avoidance algorithm that is applicable to a system with multiple instances of each resource type
ALGORITHM:
Step 1: Start the Program
Step 2: Get the values of resources and processes. Step 3: Get the avail value.
Step 4: After allocation find the need value.
Step 5: Check whether its possible to allocate. If possible it is safe state
Step 6: If the new request comes then check that the system is in safety or not if we allow the request.
Step 7: Stop the execution 10.Stop the program 

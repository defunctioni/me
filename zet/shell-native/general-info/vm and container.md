# How are Virtual Machines and Containers Different?

## Virtual Machines - Abstraction of the Physical Hardware
* Need to borrow hardware resources of the local machine. 
* Useful for running different applications with varying dependencies in isolation using a Hypervisor.
* Hypervisors are software used to create and manage virtual machines. Cross-Platform hypervisors included VirtualBox and VMWare while Hyper-V is 
a Windows only hypervisor.
* Because the whole OS needs to be loaded on start-up, just like if it were another machine, VM's are slow to start.





## Containers - Isolated Environment used to Run Applications
* Don't need to borrow the hardware of the local machine.
* Also allow running multiple apps in isolation. 
* Because containers use the OS of the local machine, the start-up has little waiting time. 
* Less hardware resources are required so they can run 10s or 100s of applications side-by-side.


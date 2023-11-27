### OS
------

TimeSharing Cpu vs Multicore cpu with more than 1 ALU.

Tightly coupled CPU , Distributed Systems (Multiple Computer communicate in same network LAN)
Clustered Systems (Multi Computers share same storage).

Realtime Systems : Hard Realtime vs Soft Realtime.

Handheld Systems like PDA:personal digital assisstant (phones).

Connection between : CPU / IO Devices / RAM.

MMU : Memory management unit.

Device Controller : Interface between connected device like mouse and computer

CPU can run only one process at a time.

All os are interrupt driven systems with interrupt service routine.

HW vs SW interrupt >> Who caused the interrupt to happen like IO Interrupt is HW.

Process can access memory even if cpu is asleep but only in limited locations for it.

MMU will wake cpu if a process tried to access memory placed not permitted.

Bootstrap : boot from ROM on motherboard
	
boot record contains windows linux and any installed system.

boot record can be edited manually by using a tool.

Device status : idle, not functioning, busy.

memory acessed through buffer for low speed IO devices.

Direct Memory Access (DMA): For high speed IO Devices communicate with memory.

Storage According to speed:

Registers << Cache << main memory << electronic disk << magnetic disk << optical disk << magnetic tapes

IR(instruction register)..PC(Program counter holds address for next instruction to be executed).

Stack & Heap :

stack : is fixed size reserved for every app in memory for certain use
	usually contains local variables, method parameters.

heap : size reserved for app but can be changed always.

HW Protection : Memory, CPU, HardDrive (Protection).

System Calls directly to kernel : File Management, Device Management, IPC Communication, Process Control.

Context Switch : Time needed to switch between process that finished and process that about to start.

Process : Child process can be terminated by parent process.

After process is terminated or finished all resources are deallocated and ready to be used.

IPC(InterProcess communication) can be done by : memory sharing, message passing.

dispatch latency: time taken by dispatcher to stop process and start another.

waiting time vs response time vs turnaround time.

CPU Scheduling algorithms (preemptive & non preemptive).

Deadlock : resource locked by certain process.

Recovery from Deadlock : By killing process by process and try to find the process holding the resource.

Preventing deadlock is much cheaper and easier than recovering from it.

Linux Architecture
•	Kernel
    -Main part of Linux
    -Talks to hardware (CPU, memory, disk)

•	User Space
    -Where users and commands run (ls, ps, top)

•	systemd (Init)
    -First process (PID 1)
    -Starts and manages all services

Processes
•	Process = running program
•	Each process has a PID

Process States
•	Running (R) – using CPU
•	Sleeping (S) – waiting
•	Stopped (T) – paused
•	Zombie (Z) – finished but not cleaned

systemd
•	Manages system services
•	Starts services at boot
•	Restarts failed services
Example:
•	systemctl status nginx

5 Daily Linux Commands
•	ps – show processes
•	top – CPU & memory usage
•	systemctl – manage services
•   uname - kernal name
•	kill – stop process

Why Important for DevOps
•	Fix CPU/memory issues
•	Manage servers easily


# Linux-Stateless-Bi-directional-Firewall
Implemented a Linux Stateless Bi-directional Firewall
1. Written in C language
2. Filter package for inbound and outbound directions
3. Allow user to define policy and policy list with priority
4. Each policy involved source/destination IP, port, protocol and action


Project Architecture
1. User Input Interface
2. Netfilter
3. Procfs Virtual File System

User interact with kernel through Proc, proc file created for user to add/delete policy. Then kernel module look through proc file to match policy

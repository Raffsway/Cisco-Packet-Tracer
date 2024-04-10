# Static Route: Packet Tracer
I designed this hypothetical network for study purposes. Using static routing and subnetting concepts, I aimed to create a laboratory with the following scenario: building an infrastructure in a network where the goal was to connect departments to distinct subnets. This idea arose with the purpose of promoting security and reducing the number of available hosts to enhance IP management quality. Consequently, only a set amount of hosts can be contained within the subnet, as we will see later.
## Departments: 3
Each switch represents a department.
- Department: A
- Department: B
- Department: C
### Department: A		   
     - Gap: 192.168.100.0 até 192.168.100.7           
     - Network: 192.168.100.0
     - Broadcast: 192.168.100.7
     - Hosts: 6
### Department: B
     - Gap: 192.168.100.8 até 192.168.100.15
     - Rede: 192.168.100.8
     - Broadcast: 192.168.100.15
     - Hosts: 6
### Department: C
     - Gap: 192.168.100.16 até 192.168.100.23
     - Rede: 192.168.100.16
     - Broadcast: 192.168.100.23
     - Hosts: 6
## Routers: 3
Each router represents a distinct geographical location.
- Router - A
- Router - B
- Router - C
### Router: A
    - Gap: 200.168.100.0 até 200.168.100.3
    - Network: 200.168.100.0
    - Broadcast: 200.168.100.3
    - Hosts: 2
### Router: B
    - Gap: 200.168.100.0 até 200.168.100.3
    - Network: 200.168.100.0
    - Broadcast: 200.168.100.3
    - Hosts: 2
### Router: C
    - Gap: 200.168.100.0 até 200.168.100.3
    - Network: 200.168.100.0
    - Broadcast: 200.168.100.3
    - Hosts: 2

# Static Route: Packet Tracer
I designed this hypothetical network for study purposes. Using static routing and subnetting concepts, I aimed to create a laboratory with the following scenario: building an infrastructure in a network where the goal was to connect departments to distinct subnets. This idea arose with the purpose of promoting security and reducing the number of available hosts to enhance IP management quality. Consequently, only a set amount of hosts can be contained within the subnet, as we will see later.
![Static Route and Subnets](https://github.com/Raffsway/Packet-Tracer-RIP/assets/145021073/ee2f3a29-59c0-4985-b980-79945ff07750)
# Departments: 3
Each switch represents a department.
- Department: A
- Department: B
- Department: C
### Department: A		   
     Gap: 192.168.100.0 - 192.168.100.7          
     Network: 192.168.100.0/29
     Broadcast: 192.168.100.7/29
     Gateway: 192.168.100.1/29 | Port: GigabitEthernet 0/1
     Hosts: 6
     
### Department: B
     Gap: 192.168.100.8 - 192.168.100.15
     Network: 192.168.100.8/29
     Broadcast: 192.168.100.15
     Gateway: 192.168.100.9/29 | Port: GigabiteEthernet: 0/0
     Hosts: 6
     
### Department: C
     Gap: 192.168.100.16 - 192.168.100.23
     Network: 192.168.100.16/29
     Broadcast: 192.168.100.23/29
     Gateway: 192.168.100.17 | Port: GigabitEthernet 0/2
     Hosts: 6
     
# Routers: 3
Each router represents a distinct geographical location.
- Router - A
- Router - B
- Router - C
### Router: A and B
    Gap: 200.168.100.0 - 200.168.100.3
    Network: 200.168.100.0/30
    Broadcast: 200.168.100.3
    Gateway Route A: 200.168.100.2/30 | Port: GigabitEthernet 0/2
    Gateway Route b: 200.168.100.1/30 | Port: GigabitEthernet 0/2
    Hosts: 2

### Router: A and C
    Gap: 200.168.100.4 - 200.168.100.7
    Network: 200.168.100.4
    Broadcast: 200.168.100.7
    Gateway Route A: 200.168.100.5/30 | Port: GigabitEthernet 0/0
    Gateway Route C: 200.168.100.6/30 | Port: GigabitEthernet 0/0
    Hosts: 2
    
###  Router: B and C
    Gap: 200.168.100.8 - 200.168.100.11
    Network: 200.168.100.8
    Broadcast: 200.168.100.11
    Gateway Route B: 200.168.100.10/30 | Port: GigabitEthernet 0/0
    Gateway Route C: 200.168.100.9/30 | Port: GigabitEthernet 0/0
    Hosts: 2

# Ping
![Ping](https://github.com/Raffsway/Packet-Tracer-RIP/assets/145021073/954f42a8-de3f-4bd5-be73-7879e1df1ae6)
As can be observed, network connectivity works perfectly. However, to test the effectiveness of the project idea in Department C, I decided to place a PC outside the subnet address range and tested connectivity. The result was "Destination host unreachable," as the address 192.168.100.25 is outside the subnet of Department C, as mentioned earlier.

    

    

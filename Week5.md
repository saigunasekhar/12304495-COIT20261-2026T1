# TASK 1:

![gns](./images/Vlan-Basics-12304495.05.png)

Task 1 is about how devices on a network find each others hardware addresses, which are called MAC addresses using something called ARP. So when one device wants to talk to another it first looks at its ARP table to see if it already knows the MAC address for the other devices IP address. If it does not know the MAC address it uses ARP to figure it out. Then it adds this new information to the table.
If you look at the ARP table before and after devices talk to each other you can see how the information, in the table changes as devices communicate with the ARP table and each other. The ARP table gets updated with entries as devices start talking to each other.

![gns](./images/Vlan-Basics-12304495.02.png)

![gns](./images/Vlan-Basics-12304495.03.png)

![gns](./images/Vlan-Basics-12304495.04.png)

# Task 2:

![gns](./images/Vlan-Basics-12304495.01.png)

Task 2 is different from Task 1. It is about how computers talk to each other on networks. We use something called default gateways. Routing to make this work.
We make small networks called subnets and we use routers to connect them. Every computer on these networks has its IP address and a default gateway. This helps the computer send information to computers that are not on its own network.
The routers are special because they can forward information from one network to another. When we can ping computers on networks it means that the routing is working correctly. This is not like Task 1 where computers can only talk to each other if they are on the network. Routing in Task 2 makes it possible for computers, on networks to communicate with each other.

![gns](./images/Vlan-Router-12304495-ping.png)


![gns](./images/Vlan-Router-12304495-ports.png)


![gns](./images/Vlan-Routers-12304495-ports1.png)

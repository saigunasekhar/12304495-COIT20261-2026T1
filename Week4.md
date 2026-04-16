![gns](./images/view-routes-12304495-network.png)

In Task 1 we set up a network with three hosts, one switch and one router. This created two subnets: 10.10.10.0/24 and 10.10.11.0/24.
Each host was given an IP address and a default gateway that pointed to the router.
The hosts did not forward IP packets,. The router did. This helped packets move between networks.

![gns](./images/view-routes-12304495-host1.png)

The routing tables were checked using the ip route show command.
The results showed that each host had a route to its own subnet and a default route through the router.
The router had routes to both subnets.

![gns](./images/view-routes-12304495-host2.png)
![gns](./images/view-routes-12304495-ping.png)

We used the ping command to test connectivity between the two subnets.
The test was successful with no packet loss and low latency.
This meant the router was correctly directing traffic between networks.
It also showed how important routing tables and default gateways are for communication between networks
The router and routing tables helped the hosts in the two subnets to communicate with each other.
The default gateways on the hosts and the IP forwarding, on the router made this communication possible.

![gns](./images/view-routes-12304495-router.png)

# TASK 2:

![gns](./images/OSPF-BASICS-1204495-NETWORK.png)

In Task 2 we set up a network using OSPF, which's a dynamic routing system. This network had two hosts and four routers. We did not set up the routing information by hand like we did in Task 1. Instead OSPF let the routers find each other and share information about how to route data. The routers then made their routing tables. These tables showed which networks the data was going to and which routers to go through to get there. There were ways for the data to get from one host to the other especially through FRR-2 and FRR-3. At first the data went through the route that OSPF thought was best. Then we cut a connection on the path using the NETem node. OSPF quickly changed the routing tables. Sent the data through the backup path. This showed how OSPF dynamic routing is good at dealing with changes in the network and keeping the connection working. The OSPF system is really useful, for making sure the network is reliable. We used OSPF to make the network work well.

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
![gns](./images/view-routes-12304495-router.png)
![gns](./images/OSPF-BASICS-1204495-NETWORK.png)

#AIMS Networking/Security Project 1 – Due Friday 10 Feb 2017

You need to build the following network in GNS3:




This network has some special requirements:

1. The PCs connected to SW1 are on a corporate network, they should be able to reach all other machines, but other machines should not be able to reach them.  They should still be able to reach each other.  The machines on SW1 should be behind a NAT.

2. The PCs connected to SW2 should be able to reach the machines connected to SW3, but NOT the machines connected to SW1.  The machines connected to SW1 should be able to reach the machines connected to SW2.

3. Machines connected to SW1 and SW2 should be able to reach SW3 and vice versa, but machines connected to SW4 should not be able to reach machines connected to SW 3.

4. Machines connected to SW4 should be publicly addressed and should be reachable by any of the machines (its ok if they can’t be reached by machines connected to SW3 but bonus points if they can while still satisfying requirement 3).

You can use any combination of the following routing technologies to complete this assignment:
- Network Segmentation
- VLANs
- Static Routing
- RIP, IGRP, or OSPF
- ACLs
- Cisco Firewall

When you are finished, you should export a portable project file from GNS3 and email it.

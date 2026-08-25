# Enterprise Multi-VLAN Network with OSPF, DHCP, NAT & ACL Security
Project Overview:

This project demonstrates the design and configuration of an enterprise-level network using Cisco Packet Tracer. The network integrates VLAN segmentation, inter-VLAN routing, OSPF dynamic routing, DHCP, NAT/PAT and ACL-based security to provide efficient, scalable and secure network communication.

 Project Objectives:

- Design an enterprise-style network topology
- Implement VLAN-based network segmentation
- Configure inter-VLAN routing
- Implement OSPF for dynamic routing
- Configure DHCP for automatic IP address allocation
- Implement NAT/PAT for external network access
- Configure ACLs for network security
- Enable secure remote device management using SSH
- Test and verify end-to-end connectivity

Phase 1 — Device & Interface Preparation
• Place the routers, switches, clients and services required by the design.
• Connect the devices using the planned physical/logical links.
• Open each device CLI and move to the correct Cisco IOS mode before entering configuration commands.
• Configure interfaces with the addressing plan and ensure required interfaces are enabled.
• Verify interface status before moving to routing or services.


Phase 2 — VLAN Configuration
• Create the required VLANs.
• Assign access ports to the correct VLANs.
• Configure trunk links where multiple VLANs must cross the same physical link.
• Verify VLAN membership and trunk operation.

Phase 3 — Inter-VLAN Routing
• Create Layer-3 gateway interfaces for the VLAN networks using the routing design used by the topology.
• Ensure each VLAN has a reachable default gateway.
• Test communication within a VLAN and then between selected VLANs.

Phase 4 — DHCP
• Create DHCP scopes/pools for the client networks.
• Define the correct network and default gateway.
• Provide DNS server information where required.
• Exclude reserved addresses when necessary.
• Check that clients obtain valid addressing automatically.

Phase 5 — DNS
• Enable/configure the DNS service.
• Create the required records.
• Point clients to the DNS server.
• Test name resolution from a client.

Phase 6 — NAT/PAT
• Identify the inside and outside interfaces.
• Define which internal addresses are eligible for translation.
• Configure the required NAT/PAT method.
• Generate traffic and verify that translations appear.

Phase 7 — ACL Security
• Write the intended security policy before applying the ACL.
• Create ACL statements in the correct order.
• Remember that ACL processing is sequential.
• Apply the ACL to the correct interface and direction.
• Test both traffic that should be allowed and traffic that should be denied.

Phase 8 — SSH Management
• Prepare the device identity/domain requirements used by SSH.
• Create a local management account where required.
• Enable the SSH service and restrict the VTY lines appropriately.
• Test remote login from an authorised client.

Phase 9 — OSPF
• Enable OSPF on the participating routers.
• Advertise the required networks.
• Use compatible OSPF area/settings between neighbours.
• Verify that expected routers become OSPF neighbours.
• Check the routing table for dynamically learned routes.


Conclusion:
This project demonstrates the practical relationship between switching, routing, services and security in an
enterprise network. VLANs provide segmentation; inter-VLAN routing connects selected networks; DHCP
automates addressing; DNS provides name resolution; NAT/PAT handles address translation; ACLs enforce
traffic policy; SSH provides secure management; and OSPF provides dynamic routing between routers.
The key lesson is that networking is not simply about entering commands. Every configuration must have a
purpose and every important configuration must be verified. The OSPF neighbour check on R1 is a clear
example: the command does not change the network; it provides evidence that the routing relationship
exists.
Together, the Packet Tracer project, the GitHub repository and this printed documentation form a complete
learning archive of the enterprise networking work

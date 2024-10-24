# Telecommunication-network



Technologies Implemented

* Design Tool- Use Cisco Packet Tracer to design and implement the network solution.
* Hierarchical Design- Use a hierarchical model providing redundancy at every layer.
* ISPs- The network is also expected to connect to a Seacom ISP Router.
* WLC- Each department is required to have a WAP providing both employees and guest WIFI managed by WLC.
* VoIP- Each department should have IP phones.
* VLAN- The LAN, WLAN, and VoIP VLANs remain at 50, 60 & 101 respectively for the entire network.
* EtherChannel- Use standard LACP as a method of link aggregation.
* STP PortFast and BPDUguard- configure the two protocols to enable faster port transition from blocking to forwarding.
* Subnetting- Provided the networks above, carry out subnetting to allocate the correct number of IP addresses to each department.
* Basic settings- Configure basic device settings such as hostnames, and console passwords, enable passwords, and banner messages, encrypt all passwords, and disable IP domain lookup.
* Inter-VLAN Routing- Devices in all the departments are required to  communicate with each other with the respective multilayer  switch configured for inter-VLAN routing.
* Core Switch- The Multilayer switches are expected to carry out both routing and switching functionalities and thus will be assigned IP addresses.
* DHCP Server- All devices in the network (except IP phones) are expected to obtain an IP address dynamically from the AD servers located at the server farm site.
* Cisco 2811 Router- Ensure to have a router that can support telephony service i.e Cisco Catalyst 2811(the VoIP router should be connected to the l3-switch).
* Static Addressing- Devices in the server room are to be allocated IP addresses statically.
* Telephony Service- Configure VoIP on the voice gateway router and allocate dial numbers in format (1...).
* Routing Protocol- Use OSPF as the routing protocol to advertise routes both on the routers and multilayer switches.
* Standard ACL for SSH- configure a simple standard ACL on the line VTY to allow only the Senior Network Security Engineer to carry out all remote administrative tasks using SSH.
* Cisco ASA Firewall- Configure security levels, zones, and policies to define how resources are accessed in the network

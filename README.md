# Practice Labs Description
Lab 1:Basic Device Security
      In this lab, we have configured encrypted and un-encrypted passwords on both router and switch.

Lab 2: Static Routing
       Here we are configuring the static router from PC --> R1--> R3 --> R4 --> PC2
       command used:
        Router(config)# ip route [destination_network_ ip_address] [destination_subnet_mask]  [exit_router_ip_address]

Lab 3: VLSM (Variable Length Subnet Mask) + Static routing
       Here we are using VLSM to confirgure 4 LANs from ip address 192.168.5.0/24 and then configure the static route on each each router.

Lab 4: VLAN 
       Here we have divided a local network in different VLAN(Engineering, Sales and HR). These are connected to each other with a switch and for communication between different VLANs, we have also 
       configured separate Router interfaces for each VLAN.

Lab 5:  VLAN trunking + Router-on-Stick
        In this topolgy we had configured a trunk between SW 1 and SW2 and then had configured Router-on-Stick for communication between different VLANs.

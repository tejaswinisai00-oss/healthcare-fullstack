\# Routing Design



Routing Overview



The healthcare application uses Layer 3 routing between VLANs.



Networks



VLAN 10 - Users

VLAN 20 - Servers

VLAN 30 - Management

VLAN 40 - Guest



\## Routing Policies



Default route points to the internet firewall.

Inter-VLAN routing is performed by the Layer 3 switch.

Guest VLAN is isolated from internal resources.


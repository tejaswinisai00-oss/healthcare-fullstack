\# VLAN Design



\## VLAN Overview



This document defines the VLAN structure for the healthcare fullstack project.



\## VLAN Details



| VLAN ID | VLAN Name | Subnet | Purpose |

|---|---|---|---|

| 10 | Users | 192.168.10.0/24 | End-user access |

| 20 | Servers | 192.168.20.0/24 | Application and database servers |

| 30 | Management | 192.168.30.0/24 | Network device management |

| 40 | Guest | 192.168.40.0/24 | Guest internet access |



\## Notes



Users should not directly access management VLAN.

Guest VLAN should be isolated from internal resources.

Servers VLAN should only allow required application traffic.


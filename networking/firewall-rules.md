\# Firewall Rules



Basic Security Rules



| Source | Destination | Port | Action | Purpose |

|---|---|---|---|---|

| Internet | Web Server | 443 | Allow | HTTPS access |

| Web Server | Database Server | 1433 | Allow | Application database access |

| Guest VLAN | Internal Network | Any | Deny | Block guest access |

| Management VLAN | Network Devices | SSH | Allow | Admin access |


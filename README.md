# firewall-on-windows
setup and use a firewall on windows
steps followed:
1. opened windows defender firewall with advance security
2. clicked inbound rules> New rule
3. selected:
   rule type: Port
   port number: 21 (FTP )
   action: Block the connection
   profile: all
   name: "Block FTP port 21"

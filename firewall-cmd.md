# Firewall-cmd Commands

### List Allowed Services
`firewall-cmd --list-services`

### List Allowed Ports
`firewall-cmd --list-ports`

### Get Default Zone
`firewall-cmd --get-default-zone`

### Allow Service for Zone
`firewall-cmd --zone={ZONE} --add-service=HTTP`

### Allow Port for Zone
`firewall-cmd --zone={ZONE} --add-port={PORT}/{tcp/udp}`


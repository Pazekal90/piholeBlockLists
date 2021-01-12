# piholeBlockLists
My collection of working block lists for the pihole application that in my cases does not block content that shouldn't be blocked to have best surfing and gaming experience in our network at home.

To add those lists in pihole just go into the pihole admin panel under "Group Management" > "Adlists" and paste the comma separated list in the field and save. The pihole will automatically cut the list in their pieces and adds the urls on by one. DONE. Have fun.

At the moment those lists contain nearly 400.000 suspicious servers oder Ad platforms. 

# My Setup
- Synology DS218+.
- Installed piHole as docker container.
- DHCP provides the Synology IP-Address as primary DNS Server in the whole network.
- In front of my FritzBox router their is a Turris Shield firewall in a separate subnet to protect the whole network from attacks.
- Guest wifi is separate to have better security and does not have the dns routed to the pihole, so the private network is completely separated.

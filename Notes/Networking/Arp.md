# ARP (Address resolution protocol)

    Address resolution protocol (ARP) maps device's logical IP address (layer
    3)to its physical MAC address (Layer 2) on a local network.it is essential
    for packet delivery, as harware needs physical address to route data .

# How Arp Works ?
    
    - Arp Cache ... if a device wants to send a data to another computer on
    a network and its know that computers ip address then it will look at 
    arp cache to see the MAC address mapped to that ip address ... if it does
    not have any MAC address mapped to that ip address ... then it sends the
    Arp request to All the devices on the LAN ... saying "who has this ip 
    address" and if a device has that ip address then it replies with ARP 
    saying that "I have that address and my MAC address is xxxxxxx" ...then
    the sending device will map and cache that MAC address for future communic
    ation...

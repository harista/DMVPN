# DMVPN  Network Design
I built a DMVPN tunnel between my home and other site. You can find how I did that.


There are two sites in this setup. DMVPN has got large scalability that you can have hundreds of sites to communicate each other.


Site1: REMRAAM-RTR-DMVPN (This will act as the Hub Router in my setup)
Site2: MARINA-RTR-VPN (This will be the only spoke router in this setup)

Notes: This VPN tunnel is built based on Dynamic Multipoint VPN. With EIGRP for routing and iPsec in Transport mode for data encyription.


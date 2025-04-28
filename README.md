# haproxy-keepalived-lb
Docker compose for containers running HAProxy &amp; Keepalived for bare metal load balancing

## How to identify the interface on your Docker host
The interface required will be the interface that serves the local network IP on your Docker server. 

Use `ip addr` to list all interfaces and identify the one with your LAN IP



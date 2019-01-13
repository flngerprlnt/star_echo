# star_echo
## STAR-ECHO (Servers That Are Running-Echo) - What is running? | Test

Web browser allow to load resources from private IP addresses (10.0.0.0 – 10.255.255.255/172.16.0.0 – 172.31.255.255/192.168.0.0 – 192.168.255.255).
Thus, it is possible to ascertain if specific software is used by the client. Loading local resources also exposes information about the router (vendor/version) the client is connected to or VPN network/provider information, IoT devices in the same network, NAS services, media/stream server and anything else that is accessible via http from the client's system.

## Extracted information (exemplary cases):

  Your router is available via 192.168.178.1
  
  Your router is : FRITZ!Box
  
  Your are running XAMPP with default configuration
  
  SABnzbd is running on port 8080
  
  SABnzbd is running on port 8082
  
  NZBGet is running on port 6789
  
  MPC-HC/BE WebServer is running on port 13579
  
  Plex is running on port 32400.
  
  Emby is running on port 8096
  
  Subsonic is running on port 4040

## How to block local requests?

  block local resource requests by system firewall
  
  configure a proxy (e.g. SOCKS v5) on your system mapped to e.g. 127.0.0.1:1080

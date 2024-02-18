We will create a 3-nodeUbuntu 20.04cluster. Using 3 nodes allows an understanding of some issues and configurationsfound in a production environment.  Currently 2 vCPU and 8G of memory allows for quick labs.  As we will be working withimages it is suggested that you allocate at least20Gof disk space for the control plane (cp) node, more is better. Other Linuxdistributions should work in a very similar manner, but have not been tested.

- 2 CPU
- 8G memory
- 20G+ disk on control plane node
- Don’t use 192.168 network for nodes
- No firewall
- Disable swap
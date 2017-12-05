# Two Openstack Heat Templates have been provided to quickly build out the infrastructure below which I used to create the VPNaaS demonstration video

![multivpn_proposalv4](https://user-images.githubusercontent.com/9472095/33618728-410a7384-d9db-11e7-96f0-a212f945302c.jpg)

Please note that you will need to amend the input parameters of the Openstack templates to match your target regions.
Once the stacks have built successfully ensure to do the following before trying to build out the VPNaaS Demo
 - set the external network as the gateway on all routers
 - assign a global ip address to all subnet gateways that will be the target of a VPN's CIDR
 - assign a global IP to the servers for testing purposes
 - add the necessary routing to the PROD-RTR for communication between the subnets
 - ping all peer addresses to ensure basic layer 3 connectivity
 
 Once you've satisfied the above prerequisites it time to start building your VPNs - 
 see : https://allthingscloud.eu/2017/11/18/vpnaas-simplified-on-fujitsu-k5/
 
 and : https://cnets-vpnaas.uk-1.cf-app.net/
 
 The Movie -> https://www.youtube.com/watch?v=aXzVHXx30xw
 
 

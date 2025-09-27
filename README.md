# Network Trouble Shooting

# Common Issues
Common network issues can be broken down in 2 sub-categories
- Partial loss of resources
- Total loss of resources

Impact and severity analysis should be the first priority

## Partial Loss
1. Virusses on the network
2. Can't access resources
3. Network is slow (**DNS** is usually the problem)

## Total Loss
1. Narrow Wireless Bandwidth
2. IP management
3. Remote access (using a VPN)

# Coporate Issues

## Is email local or on the cloud
Make sure DNS points from local infrastructure to the cloud provider.

## How are we connected?
Wifi, LAN, VPN, MAPI

## Email Protocols
Outlook Web Access, POP3 and IMAP

## Firwalls
Are firewalls configured properly if users are outside the network?

## Internal Site Issue via DNS
Public domain is also the name of the active directory domain 
then users try to connect to email internally rather than to the cloud
where the email's being hosted.

## ISP outage?

## Where does the connection stop?
Routing issues? Find out where the beginning and ending is.

## Caused by DNS?
Public DNS issue?

## IP exhaustion
We have a certain number of IP addresses in our DHCP scope and those IP can become exhausted.
We then need to add additional IPs to the scope or set up and additional scope.

## Computer Firewall Issue
Windows firewall issue or a anit-malware program can also have it's own firewall. 

# Common Cloud Issues
1. Is the port open to the cloud properly?
2. VPN to the cloud service down? Many times access to Azure or AWS we need to setup a VPN tunnel from office to the cloud resources.
3. If we can access other resources then we will need to check the connection to the cloud resource.

# Video Conferencing
1. Jittery sound/video
2. QoS set up correctly? Limited bandwidth? Setup priority to video/audio calls.
3. Possible ISP upload increase speed. -> Usually faster download speed.

# IP structure

One issues is setup of a incorrect subnet mask. While the host has an incorrect subnet mask like 255.255.00 and the network is 192.168.1.

Issues can occur on DNS, Gateway and Routing
1. DNS server valid? - Name  resoltion
2. Gateway - Points to the door to leave the network
3. Routing - Driver that helps to leave the network









# Ticket 7: Network Configuration. 

## Configure networking on serverb.

## Requirements:

- Configure a persistent static IPv4 address:
	192.168.122.25/24
- Default gateway:
	192.168.122.1
- DNS server:
	192.168.122.10
- Configure hostname:
	backup.lab.local

--- 

## Execution:

### Check the network interface name: enp1s0
![check interface](/images/ticket_7/check_network_interface.jpg)

### Configure the network setting for interface enp1s0:
![Network Configuration](/images/ticket_7/network_interface_configuration.jpg)

### Hostnme Configuration and verification:
![Hostname](/images/ticket_7/hostname_configuration.jpg)

### Ip Address Verification: 
![ip address](/images/ticket_7/ip_address_verified.jpg)

### Verify Network Configuration: (
![Network COnf](/images/ticket_7/gateway_and_dns_verified.jpg)

### Test Connectivity with Main Server: 
![Test Connection](/images/ticket_7/test_connection_with_main_server.jpg)


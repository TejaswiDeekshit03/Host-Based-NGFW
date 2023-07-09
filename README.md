# Host-Based-NGFW
This project deals with the designing of a host-based next-generation firewall that is cost-effective.
Problem Definition -

A network firewall is a security system designed to monitor and control incoming and outgoing network traffic based on predefined security rules. Its main function is to block unauthorized access while allowing legitimate traffic to pass through.
A firewall can be implemented in both hardware and software and can be configured to inspect traffic at different levels, including packet headers, transport layer, and application layer. The firewall rules define what traffic is allowed to pass through the network and what traffic is blocked.

Project Objectives - 

Since firewalls are very expensive for small organizations and they find it very difficult to install them for security purposes, therefore our NGFW can help those organizations to perform security practices. 

Creating an effective and affordable network firewall that incorporates packet filtering, logging, Network Address Translation(NAT), etc in its inventory.

Methodology - 

When a user tries to navigate to a website, the browser sends the request to the proxy server, asking it to get the requested page on his behalf. The proxy establishes a new connection to the remote site and returns the response to the browser. The browser asks the proxy to establish a virtual tunnel between itself and the remote server and then sends encrypted data through the proxy. The domain name to which a virtual tunnel is being established is usually known, so a proxy can block this virtual tunnel when it finds out that the domain name belongs to a prohibited category. After an established trust browser can ask a proxy to connect to a remote site safely with HTTPS, the proxy can decrypt the traffic, filter it, encrypt it again and pass it to the browser. As the browser trusts the proxy it continues working with filtered HTTPS without any errors or warnings.

Technology - 

Python - Pcap, Asyncio, Diesel, Twisted, nfqueue, dpkt
The Squid proxy cache server is an excellent solution to a variety of proxy and caching server needs, and scales from the branch office to enterprise-level networks while providing extensive, granular access control mechanisms, and monitoring of critical parameters via the Simple Network Management Protocol (SNMP). 

Functional Specifications - 

Here are some functional specifications of a network firewall:

Packet filtering: A firewall must be able to examine each packet that enters or leaves the network and determine whether to allow it or block it based on a set of rules.

Access control: A firewall should be able to control which users or systems can access which resources on the network.

Port blocking: A firewall must be able to block specific ports used for certain services, such as file sharing or remote access.

Logging: A firewall should log all traffic passing through it, including the source and destination IP addresses, port numbers, and protocol used.

Network address translation (NAT): A firewall can use NAT to allow multiple devices on a private network to share a single public IP address.

Denial-of-service (DoS) protection: A firewall can detect and prevent DoS attacks by blocking traffic from sources that are flooding the network with traffic.

Application-level filtering: A firewall can inspect traffic at the application level and block specific types of traffic, such as email attachments or web content.


Project Scope - 

Design and configuration: Develop a design and configuration for the firewall that meets the identified requirements, including the type of firewall technology to be used, the placement of the firewall in the network architecture, and the rules for traffic filtering.

Testing and validation: Conduct testing and validation of the firewall implementation to ensure that it is functioning as intended, including testing for vulnerabilities and verifying that the rules and policies are correctly enforced.

Maintenance and support: Establish a plan for ongoing maintenance and support of the firewall, including regular updates and patches, monitoring and reporting of firewall activity, and troubleshooting and problem resolution.

Documentation: Create documentation for the firewall implementation, including the design and configuration, testing and validation results, maintenance and support procedures, and training materials.

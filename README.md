## Objective
The objective of this task was to configure and test basic firewall rules to allow or block network traffic using Windows Firewall.

## Tools Used
Windows Defender Firewall with Advanced Security.

## Steps Performed

1.  Accessed Windows Defender Firewall:
    * Opened the Control Panel.
    * Navigated to "System and Security" -> "Windows Defender Firewall".
    * Clicked on "Advanced settings" to open "Windows Defender Firewall with Advanced Security".

2.  Reviewed Firewall Status:
    * Verified that Windows Defender Firewall was active for Domain, Private, and Public profiles. [Screenshot (52).png]

3.  Listed Current Firewall Rules:
    * Navigated to "Inbound Rules" to view existing incoming traffic rules. [Screenshot (53).png, Screenshot (54).png, Screenshot (55).png]
    * Navigated to "Outbound Rules" to view existing outgoing traffic rules. [Screenshot (56).png, Screenshot (57).png, Screenshot (58).png]

4.  Added a Rule to Block Inbound Telnet Traffic (Port 23):
    * (You would describe the steps here, e.g., "Right-clicked on 'Inbound Rules' and selected 'New Rule...'. Chose 'Port' rule type, specified TCP port 23, selected 'Block the connection', applied to all profiles, and named the rule 'Block Telnet Inbound'.")

5.  Tested the Block Rule:
    * (You would describe how you tested here, e.g., "Attempted to establish a Telnet connection to my machine (or a specific application using port 23) from another machine/device on the network or locally using `telnet localhost 23`. Observed that the connection was blocked.")

6.  Removed the Test Block Rule:
    * (You would describe the steps here, e.g., "Navigated back to 'Inbound Rules', located the 'Block Telnet Inbound' rule, right-clicked, and selected 'Delete'.")

## Summary of How Firewall Filters Traffic
A firewall acts as a security guard for a network, controlling incoming and outgoing network traffic based on a set of predefined security rules. It functions by examining network packets against these rules.

* Inbound Rules: These rules govern traffic attempting to enter the network or system.For instance, blocking port 23 for Telnet prevents unencrypted remote access, enhancing security.
* Outbound Rules: These rules control traffic originating from inside the network or system and attempting to leave.

Firewalls can filter traffic based on various criteria, including:
* IP Addresses: Allowing or denying communication with specific IP addresses.
* Ports: Controlling access to specific services (e.g., HTTP on port 80, SSH on port 22).
* Protocols: Filtering based on TCP, UDP, ICMP, etc.
* Applications: Allowing or blocking specific programs from accessing the network.

By implementing these rules, firewalls help to prevent unauthorized access, block malicious software from communicating, and protect sensitive data, thereby significantly improving network security.

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

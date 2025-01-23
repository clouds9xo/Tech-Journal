# Tech-Journal
Lab 1 Notes: 
Ethernet Adapter Configuration (Screenshot 1)
  Connection-specific DNS Suffix: champlain.edu
  IPv4 Address: 184.171.154.68
  Subnet Mask: 255.255.255.0
  Default Gateway: 184.171.154.250
  Key Points:
  The device is connected to a network under the domain champlain.edu.
  The IPv4 address and default gateway are correctly configured.
Expanded Ethernet Adapter Details (Screenshot 2)
  DHCP Enabled: Yes
  Lease Information: Indicates DHCP is functioning, with lease starting and ending timestamps.
  Physical Address: MAC address is visible (60-CF-84-74-86-ED).
  DNS Servers:
  216.93.150.162, 216.93.145.253, 216.93.145.247
Ping Results (Local IPv4 Address)
  The local IPv4 address (184.171.154.68) was pinged.
  Replies indicate no packet loss and <1ms latency.
Ping Results (Google)
  The IP (142.251.40.196) corresponds to Google.
  Four packets sent and received with 8ms average round-trip time.
Traceroute to Google
  The path to Google’s IP (142.250.65.196) involves multiple hops through various networks (e.g., Internet2, core1.alba.net).
DNS Lookup for Bing.com
  Performed using the DNS server at 216.93.145.253.
  Resolved Bing.com’s IPv6 and IPv4 addresses.
DNS Lookup for Champlain.edu
  DNS server resolved multiple IPv6 and IPv4 addresses for Champlain’s website.





Lab 2: 

Open Packet Tracer: Launch the application and open a new project.
Add Workstations:
  Navigate to the End Devices category in the bottom-left menu.
  Select a PC (Generic PC) and drag it to the workspace.
  Repeat for additional workstations as needed.
Add Switches:
  Navigate to the Switches category in the bottom-left menu.
  Select a switch (2960 Switch) and drag it to the workspace.
  Place it near the workstations.



Select a Cable:
  Go to the Connections menu (lightning bolt icon in the bottom-left toolbar).
  Choose the appropriate cable type: Copper Straight-Through: Use to connect workstations to switches.
  Copper Cross-Over: Use to connect switches to each other.
  Console Cable: Use to access the switch CLI via a workstation.
Connect Devices: Click on the first device (e.g., PC) and select its port (e.g., FastEthernet0).
  Click on the second device (e.g., switch) and select an appropriate port (e.g., FastEthernet0/1).
  Repeat for other devices.
Check Connectivity:
  Once all devices are connected, look for green status lights on the ports. If red, troubleshoot cable type or device configurations.

Accessing the Command-Line Terminal on a PC
  Open the PC: Click on the PC icon in the workspace.
  This opens the PC configuration window.
Go to the Desktop Tab: Click on the Desktop tab at the top of the configuration window.
Open the Command Prompt: Select Command Prompt to access the CLI for the PC.
  You can now perform operations like ping, ipconfig, or test connectivity to other devices.

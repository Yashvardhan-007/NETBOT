NetBot
A versatile command and control center (CCC) for DDoS Botnet Attack Simulation & Load Generation.

Disclaimer
The use of this software and scripts downloaded on this repository is done at your own discretion and risk and with agreement that you will be solely responsible for any damage to your or other computer system or availability disruption that results from such activities. You are solely responsible for the usage in connection with any of the software, and the author will not be liable for any damages that you may suffer or incur availability disruption on other systems in connection with using, modifying or distributing any of this software. No advice or information, whether oral or written, obtained by you from the author or from this website shall create any warranty for the software.

What is NetBot?
Proof-of-Concept code that simulates a Client-Server botnet environment.
Easily helps setting up a botnet chain that reports to your CCC.
Assists in simulating DDoS attacks towards the target. (Experimental/Research Usage Only)
Requirements
Python 3
Supports
Tested on Debian, Ubuntu, CentOS and MacOS High Sierra.
FYI - Prototype Warning
This is simply a prototype code and may not fully work up to your expectations. Feel free to fork the project and modify it to meet your needs.
Currently working on making it more robust execution, look and feel features.
(under development) more attack vectors and variants. (as of now supports HTTP Flooding & Ping Flood only.)
Source Code
netbot_server.py : This is the actual CCC Server.
netbot_config.py : CCC loads the information about the targets to attack.
netbot_client.py : This is the client code (bots).
How do I setup/test NetBot?
You can test this software in a single machine itself, but the ultimate point of this software to deploy the client (bots) on different machines and the server code (CCC) on your machine.
very important Make sure you modify the CCC server address on the netbot_client.py code, else the bots will not connect to your CCC.
More to be added in Wiki section soon.



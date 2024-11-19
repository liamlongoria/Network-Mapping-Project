<h1>Network Mapping Project</h1>

<h2>Objective</h2>
Project consists of using Network Mapper (nmap) to discover an active network and simulate an attack in a virtual lab environment. Then proceeding to defend and analyze the attack in the defending machine. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Linux Terminal</b> 
- <b>Wireshark</b>

<h2>Environments Used </h2>

- <b>Linux</b>

<h2>Project Walkthrough:</h2>

**Step 1:** Created two (2) virtual machines and created NAT network to interconnect machines:

- Attacking Machine (Kali Linux; 10.0.2.5)
- Defending Machine (Ubuntu; 10.0.2.6)


**Step 2:** Updated and upgraded machines to have all of the necessary tools and functions to be used in the project.

![updateupgrade](https://github.com/user-attachments/assets/42fd8e7e-a7d5-45ef-82cb-721dc71710e2)

<br>

**Step 3:** Used nmap on attacking machine to determine if defending machine is up and running.

![nmap scan15](https://github.com/user-attachments/assets/f594918d-2c1a-4199-a22d-c7ac4685b7ae)

<br>

**Step 4:** Installed Uncomplicated Firewall (UFW) and allowed SSH connections from attacking machine on the defending machine.

![ufw setup](https://github.com/user-attachments/assets/6f0502b7-2f77-4dbf-8a84-458940052e3f)

<br>

**Step 5:** Installed Wireshark on defending machine to analyze network protocols and ran nmap again from attacking machine to simulate the attack. 

![wireshark packets](https://github.com/user-attachments/assets/181990d3-6815-4747-979c-699f2626a745)





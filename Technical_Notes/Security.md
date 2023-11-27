# Layers of Security:

Physical Security: Securing with doors/locks for switches, routes & PC`s.
Personal Security: Securing yourself from authorized people like sysadmins, security engineer who can steal your data.
Networking Security: protection of networking components, wired connections are more secured.
Communication Security: protect communication medium, network components and contents.

# Cyber Security: Cyber means things around you like operating system, network, application, data.
# IPS: Intrusion Prevention System (Like Antivirus).


# Ports
Port No | Protocol or use
--------|----------------
22|SSH
80|HTTP
443|HTTPS
53|DNS
49152->65535|Dynamic ports used by OS.
21|FTP

* use netstat -n for open ports scan.
* LANPortScan.exe tool used to show open ports.

# The CIA Triangle to ensure security: Confiditiality, Integrity, Availability. 
	Confiditiality: Means data is secret	(Encrypted).
	Integrity: Applied by hashing to make sure data isn`t changed or edited during transfer.
	Availability: Means resources are available for legitmate users.
	
# Threats: Accidental Vs Intentional on assets
	assets are anything of a value in our organization.

# Risks: 
	-Information theft.
	-Identity theft: stealing personal information.
	-Data loss or manipulation.
	-Diruption of service: prevent legitimate users from accessing services.
	
# Types of attacks:
	Passive: attacker isnt sending attacking or any traffic only capturing data (Spying).
	Active: attacker actively sending traffic, trying to change system or data.
	zero-day attack: unknown exploits.
	spoofing attack
	Phishing attack: hunting a user/lure him to use some tool/link based on his prefers or personal info.
	hijacking attack: go to session as an intruder.
	xss attack: SQL Injection Attack.
	Buffer-overflow attack: when you write on RAM.
	password attack: try to recover password from files/traffic.

# Types of malware/Viruses:
Need host program:
	Backdoor: secret entry point in a program to take administrative actions, Hard to scan or remove.
	LogicBomb: Code within SW that makes damage when a condition is met, like: time passed.
	Trojan horse: used to bypass firewall/antivirus and open some ports, pass malicious files.
	
# RedTeam(PenTest): 
	(network-web-wireless) Pentesting.
		
# BlueTeam(SOC):
	Secure network design
	OS Hardening
	Network Hardening
	Intrusion Detection
	Malware Analysis
	Threat Hunting
	
# Phases of Attacks:
1:
2:
Phase 3 Gaining access: enters system.
phase 4 Maintaining access: takes ownership and close open ports/vulnerabilities not to be used again.
phase 5 Covering Tracks: delete logs / prevent digital forensics

# Types of attackers: 
		Black: Cracker, offensive attacks to do damage 
		White: Ethical Hacker or security analyst/pen-test defensive attack to protect and scan for vulnerability.
		Grey: works both white & black for any benefit, with no honor.
		script-kiddy: someone like a kid that download anything and cause damage without realizing.
		Hacktivist: attacker with political reasons.
		Phreakers: hacker of telecommunication system (phone call).
		state sposored hacker: employed by the government.
		
# Internal Vs External Attacks:
	internal attacks are far more powerfull and 70% more effective.

# Notes:
* Exploits & Vulnerabilities are sold on dark web.
* Always update OS/Software.
* ISP Changes your public ip every weak (Dynamic).
* With permission you can tell isp to give an ip in certain date to locate a hacker/user.
* iplocation.net -> locate a website/server location.
* eg-cert: website to report attacks to government.
* Phishing: Is hunting information & Sensitive Data from users.
* Always backup your data to recover from ransomware.
* HashCal: a famous tool used for hashing.
* Checksum: 
* There is always a risk (impossible to be zero), as there always changes in technology.
* Risk = Threat x Vulnerability
* Security is important for resource access to make high availability (ex: printers).
* Security is important to protect vital data.
* authentication: is trying to access with your identity/permissions..etc
* authorization: is whether you are permitted to do something or not.

# CEH 認證主題
```
1.	Introduction to Ethical Hacking (介紹何謂道德入侵)
2.	Footprinting and Reconnaissance (蒐集蛛絲馬跡與網路勘查)
3.	Scanning Networks (網路服務與弱點掃描)
4.	Enumeration (列舉系統資訊)
5.	Vulnerability Analysis (弱點分析)
6.	System Hacking (入侵電腦系統)
7.	Malware Threats (惡意程式威脅)
8.	Sniffers (網路監聽與攻擊)
9.	Social Engineering (社交工程)
10.	Denial-of-Service (阻斷服務攻擊與傀儡網路)
11.	Session Hijacking (連線劫持)
12.	Evading IDS, Firewalls and Honeypots (規避入侵偵測/防火牆與誘捕系統)
13.	Hacking Webservers (入侵網站)
14.	Hacking Web Application (入侵網站程式)
15.	SQL Injection (資料隱碼攻擊)
16.	Hacking Wireless Network (入侵無線網路)
17.	Hacking Mobile Platforms (入侵行動平台)
18.	IoT and OT Hacking(入侵物聯網與工控)
19.	Cloud Computing (雲端運算)
20.	Cryptography (密碼學)
```

# 試題類型
### 試題類型1.資安情境敘述 ==> 問是何種攻擊? 何種技術?
```
While performing online banking using a Web browser, a user receives an email that contains a link to an
interesting Web site. When the user clicks on the link, another Web browser session starts and displays a
video of cats playing a piano. The next business day, the user receives what looks like an email from his bank,
indicating that his bank account has been accessed from a foreign country. The email asks the user to call his
bank and verify the authorization of a funds transfer that took place. What Web browser-based security
vulnerability was exploited to compromise the user?
A. Clickjacking
B. Cross-Site Scripting
C. Cross-Site Request Forgery
D. Web form input validation

C
```

```
Identify the web application attack where the attackers exploit vulnerabilities in dynamically generated web
pages to inject client-side script into web pages viewed by other users.
A. LDAP Injection attack
B. Cross-Site Scripting (XSS)
C. SQL injection attack
D. Cross-Site Request Forgery (CSRF)

B
```
```
You are tasked to perform a penetration test. While you are performing information gathering, you find an
employee list in Google. You find the receptionist’s email, and you send her an email changing the source
email to her boss’s email (boss@company). In this email, you ask for a pdf with information. She reads your
email and sends back a pdf with links. You exchange the pdf links with your malicious links (these links contain
malware) and send back the modified pdf, saying that the links don’t work. She reads your email, opens the
links, and her machine gets infected. You now have access to the company network. What testing method did
you use?
A. Social engineering       B. Piggybacking    C. Tailgating    D. Eavesdropping
A
```

```
“........is an attack type for a rogue Wi-Fi access point that appears to be a legitimate one offered on the
premises, but actually has been set up to eavesdrop on wireless communications. It is the wireless version of
the phishing scam. An attacker fools wireless users into connecting a laptop or mobile phone to a tainted
hotspot by posing as a legitimate provider. This type of attack may be used to steal the passwords of
unsuspecting users by either snooping the communication link or by phishing, which involves setting up a
fraudulent web site and luring people there.”
Fill in the blank with appropriate choice.
A. Evil Twin Attack    B. Sinkhole Attack     C. Collision Attack   D. Signal Jamming Attack

A
```

```
You are working as a Security Analyst in a company XYZ that owns the whole subnet range of 23.0.0.0/8 and
192.168.0.0/8.
While monitoring the data, you find a high number of outbound connections. You see that IP’s owned by XYZ
(Internal) and private IP’s are communicating to a Single Public IP. Therefore, the Internal IP’s are sending
data to the Public IP.
After further analysis, you find out that this Public IP is a blacklisted IP, and the internal communicating devices
are compromised.
What kind of attack does the above scenario depict?
A. Botnet Attack
B. Spear Phishing Attack
C. Advanced Persistent Threats
D. Rootkit Attack

A

```
```
Scenario:
1. Victim opens the attacker’s web site.
2. Attacker sets up a web site which contains interesting and attractive content like ‘Do you want to make $1000 in a day?’.
3. Victim clicks to the interesting and attractive content URL.
4. Attacker creates a transparent ‘iframe’ in front of the URL which the victim attempts to click, so the victim
thinks that he/she clicks on the ‘Do you want to make $1000 in a day?’ URL but actually he/she clicks on the
content or URL that exists in the transparent 'iframe' which is setup by the attacker.

What is the name of the attack which is mentioned in the scenario?
A. Session Fixation
B. HTML Injection
C. HTTP Parameter Pollution
D. Clickjacking Attack

D
```

```
An attacker is trying to redirect the traffic of a small office. That office is using their own mail server, DNS
server and NTP server because of the importance of their job. The attacker gain access to the DNS server and
redirect the direction www.google.com to his own IP address. Now when the employees of the office want to go
to Google they are being redirected to the attacker machine. What is the name of this kind of attack?
A. MAC Flooding
B. Smurf Attack
C. DNS spoofing
D. ARP Poisoning

C
```
### 試題類型2.系統架構與元件組成
```
Which service in a PKI will vouch for the identity of an individual or company?
A. KDC
B. CR
C. CBC
D. CA

D
```

```
During a black-box pen test you attempt to pass IRC traffic over port 80/TCP from a compromised web
enabled host. The traffic gets blocked; however, outbound HTTP traffic is unimpeded. What type of firewall is
inspecting outbound traffic?
A. Circuit   B. Stateful    C. Application    D. Packet Filtering

C
```
### 試題類型.技術的用途
```
Which of the following is the structure designed to verify and authenticate the identity of individuals within the
enterprise taking part in a data exchange?
A. SOA
B. biometrics
C. single sign on
D. PKI

D
```

```
Which method of password cracking takes the most time and effort?
A. Dictionary attack
B. Shoulder surfing
C. Rainbow tables
D. Brute force

D
```
### 試題類型.滲透測試工具及用途
```
John the Ripper is a technical assessment tool used to test the weakness of which of the following?
A. Passwords     B. File permissions    C. Firewall rulesets    D. Usernames

A
```

```
Session splicing is an IDS evasion technique in which an attacker delivers data in multiple, small sized packets
to the target computer, making it very difficult for an IDS to detect the attack signatures. Which tool can be
used to perform session splicing attacks?
A. tcpsplice   B. Burp   C. Hydra   D. Whisker
```
```
Which of the following tools is used to detect wireless LANs using the 802.11a/b/g/n WLAN standards on a
Linux platform?
A. Kismet    B. Abel    C. Netstumbler    D. Nessus

A
```

```

```

```

```

### 試題類型.nmap滲透測試技術
```
If you want to only scan fewer ports than the default scan using Nmap tool, which option would you use?
A. -r
B. -F
C. -P
D. -sP

B
```
```
You have successfully comprised a server having an IP address of 10.10.0.5. You would like to enumerate all
machines in the same network quickly.
What is the best Nmap command you will use?
A. nmap -T4 -q 10.10.0.0/24
B. nmap -T4 -F 10.10.0.0/24
C. nmap -T4 -r 10.10.1.0/24
D. nmap -T4 -O 10.10.0.0/24

```

```
You are attempting to run an Nmap port scan on a web server. Which of the following commands would result
in a scan of common ports with the least amount of noise in order to evade IDS?
A. nmap -A - Pn
B. nmap -sP -p-65535 -T5
C. nmap -sT -O -T0
D. nmap -A --host-timeout 99 -T1
C
```

```
What does the –oX flag do in an Nmap scan?
A. Perform an eXpress scan
B. Output the results in truncated format to the screen
C. Output the results in XML format to a file
D. Perform an Xmas scan

C
```

```
Which of the following is an extremely common IDS evasion technique in the web world?
A. Spyware     B. Subnetting    C. Unicode Characters    D. Port Knocking

C
```

### 試題類型1. 防禦技術 |countermeasure |Security Controls| Safeguard
```
Which of the following is the best countermeasure to encrypting ransomwares?
A. Use multiple antivirus softwares
B. Pay a ransom
C. Keep some generation of off-line backup
D. Analyze the ransomware to get decryption key of encrypted data

C
```

```
Which of the following is the BEST way to defend against network sniffing?
A. Using encryption protocols to secure network communications
B. Register all machines MAC Address in a Centralized Database
C. Use Static IP Address
D. Restrict Physical Access to Server Rooms hosting Critical Servers

A
```

### 試題類型1.安全協定
```
Although FTP traffic is not encrypted by default, which layer 3 protocol would allow for end-to-end encryption of
the connection?
A. SFTP   B. Ipsec   C. SSL  D. FTPS

B
```

```

```

### 試題類型1.
```

```

```

```

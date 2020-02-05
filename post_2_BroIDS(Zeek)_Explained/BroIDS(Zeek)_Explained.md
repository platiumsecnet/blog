Bro IDS (Zeek) Explained
---

# 1. What is BroIDS
Bro, which was renamed Zeek in late 2018 and is sometimes referred to as Bro-IDS or now Zeek-IDS, is a bit different than Snort and Suricata. In a way, Bro is both a signature and anomaly-based IDS. Its analysis engine will convert traffic captured into a series of events. An event could be a user login to FTP, a connection to a website or practically anything. The power of the system is what comes after the event engine and that's the Policy Script Interpreter. This policy engine has its own language (Bro-Script) and it can do some very powerful and versatile tasks.

If you're an analyst and you've wondered "How can I automate some of my work?" then this is the tool you've been looking for. Want to download files seen on the wire, submit them for malware analysis, notify you if a problem is found then blacklist the source and shutdown the user's computer who downloaded it? Want to track the usage patterns of a user after they've contacted an IP from a reputation database?

If you're not an analyst then this tool will have a challenging learning curve. Since it was developed as a research tool, it didn't initially focus on things like GUIs, usability, and ease of installation. While it does numerous cool things out of the box many of those things aren't immediately actionable and may be difficult to interpret.

There’s no native GUI but there are third-party open source tools available for a web front end to query and analyze alerts coming from Bro-IDS. Consider ELK stack.

When a security alert fires or when you have a problem to investigate, Zeek / Bro helps you find the problem—faster. It complements signature-based tools to help you rapidly trace complex events across multiple flows and protocols with ease, to quickly pinpoint and resolve security issues.

# 2. Features
1. Can detect patterns of activity other IDS systems can not
2. Very extensible architecture
3. Good community support
4. Comprehensive traffic logging and analysis
5. Powerful and flexible event-driven scripting language (Bro scripts)
6. Deploys on UNIX-style systems, including Linux, FreeBSD, and MacOS
7. DNS/FTP/HTTP/IRC/SMTP/SSH/SSL/other protocol support
8. Fully passive traffic analysis with network tap or monitoring port
9. Real-time and offline analysis
10. Cluster-support for large-scale deployments
12. Comprehensive IPv6 support
13. IDS-style pattern matching
14. File extraction
15. Analysts can use Bro for automation (file extraction, malware analysis, blacklisting, track usage patterns, research work, etc.)

# Highly-structured real time network data.
If your typical response to alerts involves digging through piles of PCAP files or trying to piece together data through thin NetFlow records, there’s a better way. It’s Zeek. Zeek / Bro generates a wide range of rich network information, including logs for:
1. conn
2. capture loss
3. dce rpc
4. dhcp
5. dnp3
6. dns
7. dpd
8. files
9. ftp
10. http
11. intel
12. irc
13. kerberos
14. modbus
15. mysql
16. notice
17. ntlm
18. radius
19. rdp
20. sftp
21. sip
22. socks
23. smb
24. smtp
25. snmp
26. ssh
27. ssl
28. tunnel
29. weird
30. x509

# 3. Disadvantages
1. Complicated to set up


# Refs
1. https://cybersecurity.att.com/blogs/security-essentials/open-source-intrusion-detection-tools-a-quick-overview
2. https://www.corelight.com/about-zeek/how-zeek-works

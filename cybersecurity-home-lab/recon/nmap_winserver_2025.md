# UDP Port and Service Version Scan (April 7, 2025)

## 🖥️ Target
- IP: `192.168.1.2`
- OS: Detected as Windows (Micro-Star Intl hardware)
- MAC: D8:CB:8A:9A:F6:29

## 🔧 Command
```bash
nmap -sU -sV -p 53,67,68,69,123,161,162,500,514,520 192.168.1.2
Port	State	Service	Version	Notes
53	open	domain	Simple DNS Plus	DNS Service running ✅
67	open	filtered	dhcps	
68	open	filtered	dhcpc	
69	open	filtered	tftp	
123	open	ntp	NTP v3	NTP Service confirmed ✅
161	open	filtered	snmp	
162	open	filtered	snmptrap	
500	open	filtered	isakmp	
514	open	filtered	syslog	
520	open	filtered	route	

# Day 2: Wireshark HTTP Analysis
**Feb 16, 2026** | Live packet capture + filtering

## Workflow
1. `tcpdump -i en0 -w sample.pcap -c 10`
2. Wireshark → Filter: `http`
3. Traffic: 172.0.1 ↔ 172.0.1 (internal)

## Findings
- **Normal internal HTTP traffic** (no attacks)
- Source/Dest: 172.0.1 (Kali UTM internal)

**Skills Gained**: Live capture, HTTP filtering, traffic analysis

![Wireshark HTTP Filter]
<img width="1920" height="1080" alt="Screenshot 2026-02-16 at 2 43 36 PM" src="https://github.com/user-attachments/assets/105762cc-6739-4cd1-bbef-967b88ab8d46" />

# CySA+ Port Security Game

An interactive matching game designed to help you master the network ports and protocols that appear on the **CompTIA CySA+ (CS0-003 / CS0-004)** exam.

Play here → **[https://YOUR-USERNAME.github.io/cysa-port-security-game/](https://YOUR-USERNAME.github.io/cysa-port-security-game/)**  
*(Replace `YOUR-USERNAME` with your actual GitHub username after enabling GitHub Pages)*

---

## Why this game?

CySA+ does not have a pure “ports” domain like A+ or Network+, but ports show up constantly in:

- **1.2** – Analyze indicators of potentially malicious activity → *Activity on unexpected ports*
- Packet analysis / Wireshark / tcpdump scenarios
- SIEM alerts and threat hunting
- Secure vs insecure protocol decisions
- nmap / reconnaissance findings

This game focuses on the ports that actually matter for a cybersecurity analyst.

---

## Game Modes

| Mode | Description |
|------|-------------|
| **Match Ports** | Classic PurposeGames-style matching. Match port numbers (TCP/UDP) to their services. |
| **Secure vs Insecure** | Decide whether a protocol is considered secure or cleartext/insecure. |
| **Unexpected Ports (IOC)** | Scenario-based questions: Is this network activity an indicator of compromise? |
| **Study Reference** | Full searchable table of every port with CySA+-relevant security notes. |
| **History** | View your previous attempts, personal bests, and progress over time (saved in your browser). |

---

## Ports Covered

Includes the core ports most likely to appear on CySA+ plus important secure alternatives and classic IOC ports:

- 20/21 (FTP), 22 (SSH/SFTP), 23 (Telnet), 25 (SMTP)
- 53 (DNS), 67/68 (DHCP), 69 (TFTP), 80 (HTTP), 88 (Kerberos)
- 110 (POP3), 123 (NTP), 137-139 (NetBIOS), 143 (IMAP)
- 161/162 (SNMP), 389 (LDAP), 443 (HTTPS), 445 (SMB)
- 465 (SMTPS), 514 (Syslog), 587 (SMTP Submission), 636 (LDAPS)
- 993 (IMAPS), 995 (POP3S), 1433 (MS SQL), 1521 (Oracle)
- 1723 (PPTP), 1812/1813 (RADIUS), 3389 (RDP), 5060 (SIP)
- **4444** (classic Metasploit Meterpreter port)

---

## How to Play Locally

1. Download `index.html`
2. Open it in any modern browser
3. No installation or server required

---

## Hosting on GitHub Pages

1. Create a new public repository
2. Upload `index.html` (and optionally this README)
3. Go to **Settings → Pages**
4. Set source to the `main` branch and `/ (root)`
5. Your game will be live at:  
   `https://YOUR-USERNAME.github.io/REPO-NAME/`

---

## License

Free for personal study and educational use. Feel free to fork and improve.

Good luck on your CySA+ exam!

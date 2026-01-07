# Linux Risky Permission Scanner

A lightweight Linux security auditing tool that scans the entire filesystem and identifies risky permission configurations that can lead to privilege escalation.

## 🚨 What It Detects
- World-writable files
- SUID (Set-User-ID) binaries
- SGID (Set-Group-ID) binaries
- Potential privilege escalation attack surfaces

## 🛠 How It Works
Uses Linux permission bits to locate dangerous files that attackers often abuse to gain elevated privileges.

## 🚀 Usage

```bash
git clone https://github.com/<your-username>/linux-risky-permission-scanner.git
cd linux-risky-permission-scanner
chmod +x risky_scan.sh
sudo ./risky_scan.sh

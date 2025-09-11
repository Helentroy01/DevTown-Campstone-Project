# 🛡️ Network Defense Toolkit – Suricata IDS Project

## Step 1 – Environment Setup
![Environment Setup](screenshots/step1_env_setup.png)  
Configured Kali Linux (attacker) and Metasploitable2 (target). Verified connectivity with `ping`.

---

## Step 2 – Suricata Setup
![Suricata Config](screenshots/step2_config.png)  
Installed Suricata, edited `suricata.yaml`, and verified rule path.

---

## Step 3 – Writing Custom Rules
![Custom Rules](screenshots/step3_rules.png)  
Added SYN Flood, DNS exfiltration, ICMP ping, and HTTP exploit rules in `local.rules`.

---

## Step 4 – Detection & Alerts
![Alerts](screenshots/step4_alerts.png)  
Ran attacks (`hping3`, `nmap`, `curl`, `dig`) and Suricata generated alerts in `fast.log`.

---

## Evidence & Toolkit
![Toolkit](screenshots/project_folder.png)  

- `local.rules` → custom detection rules  
- `suricata.yaml` → configuration  
- `PCAPs/` → captured evidence of attacks  
- `screenshots/` → step-by-step documentation  

---

## 📢 Insight
This project shows how Suricata can detect **port scans, SYN floods, ICMP probes, DNS exfiltration, and HTTP exploits**.  

### ✅ Key Defenses:
- Early detection of suspicious traffic  
- Custom rule creation for targeted threats  
- Real-time alerting & evidence capture  

---

## 🚀 Call to Action
Integrate Suricata into your blue team toolkit for continuous monitoring and automated defense.

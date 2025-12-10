# ARP Poisoning Attack (Kali Attacker → Windows Victim)

## Environment
- **Attacker (Kali Linux):** 192.168.0.108  
- **Victim (Windows):** 192.168.0.100  
- **Gateway/Router:** 192.168.0.1  
- Tools used: **Ettercap GUI**, **Wireshark**, **PowerShell**

---

## 1. Check Network Info on Victim (Windows)
On the victim machine:

```powershell
ipconfig
arp -a![WhatsApp Image 2025-12-10 at 18 12 39_a728f471](https://github.com/user-attachments/assets/9f17e6b7-25e5-4083-bdad-6f109b21fa55)


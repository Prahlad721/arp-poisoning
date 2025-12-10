# ARP Poisoning Attack (Kali Attacker → Windows Victim)

## Environment
- **Attacker (Kali Linux):** 192.168.0.108  
- **Victim (Windows):** 192.168.0.100  
- **Gateway/Router:** 192.168.0.1  
- Tools used: **Ettercap GUI**, **Wireshark**, **PowerShell**

---![WhatsApp Image 2025-12-10 at 18 04 52_8b4f719e](https://github.com/user-attachments/assets/ea7c7716-cc15-4d85-8109-bd0a5bc8df68)
![WhatsApp Image 2025-12-10 at 18 12 39_f5cdd949](https://github.com/user-attachments/assets/a1fcc5af-c16f-4790-989f-a62983638379)
![WhatsApp Image 2025-12-10 at 18 06 56_f8b4d71a](https://github.com/user-attachments/assets/48fb3ff7-c431-4ce4-9f01-99052789f5e8)
![WhatsApp Image 2025-12-10 at 18 06 56_c1ab6611](https://github.com/user-attachments/assets/a9f2bfb4-f1ce-4df4-9443-c13c622f0d6c)
![WhatsApp Image 2025-12-10 at 18 06 55_cf043aaa](https://github.com/user-attachments/assets/2a8ccfd2-a8eb-417f-a326-44c805805096)
![WhatsApp Image 2025-12-10 at 18 04 52_70a6dd3f](https://github.com/user-attachments/assets/8633d946-44f7-459f-8b44-f4ac8f51d372)


## 1. Check Network Info on Victim (Windows)
On the victim machine:

```powershell
ipconfig



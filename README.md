# 🚨 Cyber Incident: Alert System Infiltration

<p align="center">
  <img src="https://southorlandobaptist.org/wp-content/uploads/2017/09/emergency_alert_system1_1024x634_by_ericmartin375-d9877pe.png" alt="Emergency Alert System Breach" width="450"/>
</p>

This repository documents the simulated breach of a **university emergency SMS alert system**, infiltrated through credential harvesting and remote access malware. It covers attacker motivations, step-by-step remediation, lessons learned, and updated cybersecurity policies.

> 🔊 [Download narrated presentation (PPTX with audio – OneDrive)](https://1drv.ms/p/c/925E68B4556DC380/EWdX5RL3XXdItJEvHyv1K8EB43PZGtUuXz50sb2JFUlCfA?e=VqTw5E)

---

## 🛡️ Overview

**Key Concepts:**
- Social engineering attack vector via remote desktop monitoring
- Credential reuse and weak authentication exploited
- Command-and-Control (C2) connection via `STEM.EXE`
- Alert system isolation to prevent mass disruption
- SIEM alert tracking using MAC/IP fingerprinting
- Containment and policy improvements

---

## 🔐 Key Mitigations

- **Isolated affected alert system** to prevent SMS broadcasting
- **Blacklisted STEM.EXE** in SIEM
- **Implemented certificate-based authentication** (PKI)
- **Clean desk & video call confidentiality policy**
- **Gmail phishing report add-in for campus**
- **Mandatory annual cybersecurity awareness training**

---

## 🧰 Tools & Techniques

- Digital certificates / PKI
- SIEM investigation (log correlation by MAC/IP)
- Malware identification and blacklisting
- Sandbox process analysis (`STEM.EXE`)
- Incident response playbook modeling

---

## 👤 Author

**Michael Twining**  
Cybersecurity Researcher | Blue Team & Incident Response Focus  
GitHub: [@usrtem](https://github.com/usrtem)  
📫 michael.twining@outlook.com  
🎥 [YouTube](https://youtube.com/@cybergeek-mt) | 🔗 [LinkedIn](https://linkedin.com/in/michael-twining)

---

## 📜 License

This work is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

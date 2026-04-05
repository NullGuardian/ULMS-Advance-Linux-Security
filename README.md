# ULMS | Universal Linux Malware Scanner <img width="350" height="350" alt="ulms" src="https://github.com/user-attachments/assets/6aeff851-5427-409a-87e8-d23d1050f4ee" />


ULMS is a unified security app designed to simplify and strengthen Linux system protection. It integrates three industry-standard security engines—**ClamAV**, **Linux Malware Detect (LMD)**, and **Rkhunter**—into a single, high-performance workflow with a clean graphical interface.

<img width="600" height="600" alt="Screenshot From 2026-04-05 09-29-41" src="https://github.com/user-attachments/assets/fb113c04-b783-411b-a08f-40b5495b532c" />
<img width="600" height="600" alt="Screenshot From 2026-04-05 09-29-58" src="https://github.com/user-attachments/assets/a81cc4f4-2933-4698-b196-af2b335f9109" />
<img width="600" height="600" alt="Screenshot From 2026-04-05 09-30-08" src="https://github.com/user-attachments/assets/a22fa813-bec4-40c2-b07e-2f652dbf5f8f" />





## Core Protection Stack
| Engine | Specialization | Function in ULMS |
| :--- | :--- | :--- |
| **ClamAV** | Signature Scanning | Rapid detection of known virus and malware signatures. |
| **LMD** | Script & Web Threats | Specialized monitoring for web-shells and script-based exploits. |
| **Rkhunter** | Integrity & Rootkits | Deep system auditing to detect rootkits and core compromises. |

## Key Features
- **Real-Time Monitoring:** Native `inotify` integration for immediate threat detection.
- **Automated Engine Coordination:** Synchronized updates and scans across all three engines.
- **Smart Quarantine System:** Centralized vault for suspicious files with one-click restore or secure deletion.
- **Zone-Based Policy:** Intelligent automated response—notifications for user areas; auto-quarantine for high-risk system paths.
- **Health Dashboard:** Visual overview of system status, engine health, and signature database hygiene.
- **Desktop Ready:** Full desktop integration with native notifications, watchdog services, and boot management.
- **Schedule Scanning:** You choose when the scanning happens
- **Themes:** A lot of options to customise your app for better experience

## Why ULMS?
Standard security setups often leave gaps between tools. ULMS closes these gaps by providing a centralized command center. It eliminates the complexity of manual configuration, ensuring that even users without extensive command-line knowledge can deploy professional-grade security on their Linux machines.

## Installation
ULMS is distributed as pre-compiled, standalone RPM and DEB packages. Download the latest version from the Releases page.

Fedora / RHEL / CentOS (.rpm)

sudo dnf install ./ulms-1.0.0-1.fc43.x86_64.rpm


Ubuntu / Debian / Mint / Kali (.deb)

sudo apt update && sudo apt install ./ulms_1.0.0-1_amd64.deb

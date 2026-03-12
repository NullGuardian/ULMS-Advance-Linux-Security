# ULMS | Universal Linux Malware Scanner <img width="600" height="700" alt="ulms" src="https://github.com/user-attachments/assets/6aeff851-5427-409a-87e8-d23d1050f4ee" />


ULMS is a unified security orchestration suite designed to simplify and strengthen Linux system protection. It integrates three industry-standard security engines—**ClamAV**, **Linux Malware Detect (LMD)**, and **Rkhunter**—into a single, high-performance workflow with a clean graphical interface.

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

## Why ULMS?
Standard security setups often leave gaps between tools. ULMS closes these gaps by providing a centralized command center. It eliminates the complexity of manual configuration, ensuring that even users without extensive command-line knowledge can deploy professional-grade security on their Linux machines.

## Installation (Fedora / RHEL / CentOS)
ULMS is distributed as a pre-compiled, standalone RPM for ease of deployment and security. To install the suite and all its dependencies, run:

```bash
sudo dnf install ./ulms-1.0.0-1.fc43.x86_64.rpm

### 🚨 Incident Response & Threat Hunting Scripts
This is the core of the operational playbook. These scripts are designed to run in live, high-stress scenarios.

*   **[birtha](https://github.com/ArronJablonowski/birtha):** A robust, modular Bash framework for live incident response and threat hunting. Excellent for executing systematic, repeatable investigation procedures.
*   **[Kansa](https://github.com/ArronJablonowski/Kansa):** *(Under Construction)* A modular PowerShell framework designed to replicate the functionality of `birtha` for Windows environments.
*   **[ufw_log_parser](https://github.com/ArronJablonowski/ufw_log_parser):** A dedicated Bash script designed to parse Uncomplicated Firewall logs, converting raw, verbose journal entries into a clean, structured, and readable format for immediate review.
*   **[threatHunt_pcaps](https://github.com/ArronJablonowski/threatHunt_pcaps):** A powerful Bash tool designed to automate network forensics. It parses raw PCAPs to extract crucial data points like DNS queries, unusual ports, GeoIP metadata, and clear-text objects (HTTP, SMB, TFTP) for deep analysis.

### 🛠️ System Setup & Automation Scripts
These scripts automate the build process for target environments, saving hours of manual setup time.

*   **[install_zsh](https://github.com/ArronJablonowski/install_zsh):** Installs Zsh and applies a custom configuration that automatically stamps the prompt with the current time in the ISO 8601 format (`YYYY-MM-DD HH:MM:SS-Timezone`).
*   **[SIFT_Plus_Installer](https://github.com/ArronJablonowski/SIFT_Plus_Installer):** A comprehensive installer that sets up an entire SIFT Workstation environment, plus additional tools and OS hardening configurations.
*   **[install_WSL_Ubuntu](https://github.com/ArronJablonowski/install_WSL_Ubuntu):** A PowerShell script designed to quickly set up and configure a working WSL environment for Linux CLI access on Windows.
*   **[FixWinTime](https://github.com/ArronJablonowski/FixWinTime):** A simple batch file to enforce or correct the system time clock on Windows, critical for multi-OS forensic consistency.

### 🤖 AI & Workflow Integration
*   **[OpenClaw AI Setup Guide](https://github.com/ArronJablonowski/)** 🧠 **(🚧 Under Construction 🚧)**
    *   This guide outlines the complete process for setting up the AI development environment on a Mac

# Wazuh VirusTotal Threat Intelligence Integration

## Project Overview

This repository documents the complete process of integrating VirusTotal Threat Intelligence with Wazuh SIEM.

The objective of this project is to enhance Wazuh's threat detection capability by automatically querying VirusTotal whenever suspicious file hashes are detected. The integration enables security analysts to quickly identify malicious files without leaving the Wazuh Dashboard.

---

## Objectives

- Integrate VirusTotal API with Wazuh Manager
- Configure Wazuh to query VirusTotal
- Verify successful integration
- Test the implementation using sample files
- Document every step with screenshots

---

## Technologies Used

- Ubuntu Server 22.04 LTS
- Wazuh Manager
- Wazuh Dashboard
- VirusTotal Public API
- Linux
- XML
- JSON

---

## Repository Structure

| Folder | Description |
|---------|-------------|
| 01_Project_Overview | Project introduction |
| 02_Prerequisites | Required software and services |
| 03_Create_VirusTotal_API_Key | Creating VirusTotal account and API key |
| 04_Configure_Wazuh_Manager | Configure Wazuh integration |
| 05_Create_Custom_Rules | Configure Wazuh rules |
| 06_Restart_Wazuh | Restart services |
| 07_Test_the_Integration | Test VirusTotal integration |
| 08_Verification_on_Wazuh_Dashboard | Verify alerts |
| 09_Troubleshooting | Common issues and solutions |
| 10_Conclusion | Project summary |

---

## Expected Outcome

After completing this implementation, Wazuh Manager will automatically communicate with VirusTotal whenever monitored file hashes are generated, allowing analysts to determine whether detected files are malicious, suspicious, or clean.

---

Author

**Md. Mahafuz Ahmed Borshon**

Cyber Security Engineering

University of Frontier Technology Bangladesh

# Prerequisites

## Objective

Before integrating VirusTotal with Wazuh, it is important to verify that the Wazuh Manager is operational, the server has internet connectivity, and the installed Wazuh version is supported.

---

## System Information

| Component | Status |
|-----------|--------|
| Operating System | Ubuntu Server 22.04 LTS |
| Wazuh Manager | Installed |
| Wazuh Dashboard | Accessible |
| Internet Connection | Required |
| Root/Sudo Privileges | Required |

---

## Verification Steps

### 1. Verify Wazuh Manager Service

```bash
sudo systemctl status wazuh-manager
```

Expected Result:

The service status should display **active (running)**.

---

### 2. Verify Internet Connectivity

```bash
ping -c 4 google.com
```

Expected Result:

The server should successfully receive replies from Google's servers.

---

### 3. Verify Installed Wazuh Version

```bash
sudo /var/ossec/bin/wazuh-control info
```

Expected Result:

The installed Wazuh version information should be displayed.

---

## Outcome

After completing these verification steps, the server is confirmed to be ready for the VirusTotal Threat Intelligence integration.

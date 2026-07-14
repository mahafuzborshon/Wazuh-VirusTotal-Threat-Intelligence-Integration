# Restart Wazuh Manager

## Objective

After modifying the `ossec.conf` file, the Wazuh Manager must be restarted to apply the new VirusTotal integration settings.

---

## Restart the Service

```bash
sudo /var/ossec/bin/wazuh-control restart
```
<img width="692" height="689" alt="image" src="https://github.com/user-attachments/assets/e2ab4934-c0e3-4ed7-a161-ccf9646fcee4" />

---

## Verify the Service Status

```bash
sudo systemctl status wazuh-manager
```
<img width="938" height="368" alt="image" src="https://github.com/user-attachments/assets/c28e6360-a96c-411b-82e9-51dbb9e77791" />


Expected Result:

- The Wazuh Manager service is active and running.
- No XML or configuration errors are reported.

---

## Outcome

The Wazuh Manager successfully loads the updated configuration containing the VirusTotal integration.

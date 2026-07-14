# Configure VirusTotal Integration

## Objective

This step configures the Wazuh Manager to communicate with the VirusTotal API using a personal API key.

The integration enables Wazuh to automatically query VirusTotal whenever a monitored file generates a matching event.

---

## Configuration File

```text
/var/ossec/etc/ossec.conf
```

---

## Steps

1. Open the Wazuh configuration file.
<img width="1899" height="991" alt="image" src="https://github.com/user-attachments/assets/9bcde8e8-6c2d-4681-89db-e0a0cb52f74b" />

2. Add the VirusTotal integration block.
<img width="908" height="511" alt="image" src="https://github.com/user-attachments/assets/6ee5d4bc-65ef-4726-9ac8-008f2a738d21" />

3. Replace the placeholder API key with your own VirusTotal API key.
4. <img width="999" height="846" alt="image" src="https://github.com/user-attachments/assets/ebe35769-aad4-4490-9ba5-b6c32faf37f0" />

5. Save the configuration.
6. Restart the Wazuh Manager.
<img width="689" height="688" alt="image" src="https://github.com/user-attachments/assets/66afc2c2-0bd9-4ea5-af22-50d3ff3f49cb" />


---

## Expected Outcome

The Wazuh Manager loads successfully with the VirusTotal integration enabled.

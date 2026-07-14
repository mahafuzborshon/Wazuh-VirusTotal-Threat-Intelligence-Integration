# Configure Wazuh Manager for VirusTotal Integration

## Objective

This step configures the Wazuh Manager to communicate with the VirusTotal API. The configuration is added to the `ossec.conf` file and includes the VirusTotal integration block containing the user's API key.

---

## Configuration File

```text
/var/ossec/etc/ossec.conf
```
<img width="1897" height="969" alt="image" src="https://github.com/user-attachments/assets/6468edff-07b1-4f91-946f-d92af8ff5208" />


---

## Configuration Steps

1. Open the `ossec.conf` configuration file.
2. Locate the closing `</ossec_config>` tag.
3. Add the VirusTotal integration block before the closing tag.
4. Save the configuration.
5. Validate the XML syntax if applicable.
6. Restart the Wazuh Manager to apply the changes.

---

## Expected Outcome

The Wazuh Manager should load the VirusTotal integration successfully without configuration errors.

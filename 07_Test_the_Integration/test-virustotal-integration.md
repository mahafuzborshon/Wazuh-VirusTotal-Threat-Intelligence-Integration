# Test the VirusTotal Integration

## Objective

This section verifies that the VirusTotal integration is functioning correctly by generating a File Integrity Monitoring (FIM) event.

---

## Testing Procedure

1. Create a directory that is monitored by Wazuh File Integrity Monitoring (FIM).
<img width="604" height="72" alt="image" src="https://github.com/user-attachments/assets/c2527c20-dbf9-47c3-ba07-d5d27835c4af" />
<img width="705" height="367" alt="FIMTestDirectoryConfirmed" src="https://github.com/user-attachments/assets/92f9c8cd-3f34-47e8-9f70-14025aa2bb54" />

2. Generate the EICAR test file. 
3. Wait for Wazuh to detect the file.
4. Verify that Wazuh queries VirusTotal.
5. Confirm that the alert appears in the Wazuh Dashboard.

---

## Expected Result

- Wazuh detects the new file.
- VirusTotal is queried using the file hash.
- Threat intelligence information is attached to the alert.
- The alert is visible in the Wazuh Dashboard.

---

## Outcome

The successful appearance of the VirusTotal enrichment confirms that the integration is functioning correctly.

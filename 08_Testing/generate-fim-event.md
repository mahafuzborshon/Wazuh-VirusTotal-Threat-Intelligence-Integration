# Generate a File Integrity Monitoring Event

## Objective

This step generates a new file inside a monitored directory to trigger a File Integrity Monitoring (FIM) event. The event is later used by the VirusTotal integration for threat intelligence enrichment.

---

## Steps

1. Navigate to the monitored directory.
2. Create a test file.
3. Verify that the file exists.
4. Monitor Wazuh logs for file integrity events.

---

## Commands

```bash
cd /opt/wazuh-test
echo "VirusTotal Integration Test" | sudo tee test.txt
ls -l
```

---

## Expected Result

The new file is created successfully, and Wazuh detects the file during the next FIM scan.

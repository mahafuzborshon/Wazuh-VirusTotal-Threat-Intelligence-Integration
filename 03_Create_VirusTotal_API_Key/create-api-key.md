<img width="1111" height="872" alt="image" src="https://github.com/user-attachments/assets/e50365ab-8946-4222-ac8a-d008c29a4c96" /># Create a VirusTotal API Key

## Objective

VirusTotal provides an API that allows security solutions such as Wazuh to retrieve threat intelligence about suspicious files. This API key is required to authenticate requests from the Wazuh Manager.

---

## What is VirusTotal?

VirusTotal is a cloud-based threat intelligence platform owned by Google that analyzes files and URLs using multiple antivirus engines and security vendors.

Instead of scanning files locally, Wazuh sends the SHA-256 hash of a detected file to VirusTotal. VirusTotal then returns reputation information, including whether the file has been identified as malicious by any participating security vendor.

---

## Steps

### Step 1

Visit the VirusTotal website.
<img width="1094" height="869" alt="VirusTotalHomepage" src="https://github.com/user-attachments/assets/eb7f97a1-2300-4421-a362-d00bace01b16" />



### Step 2

Create a free account or sign in to your existing account.
<img width="1098" height="869" alt="APIKey" src="https://github.com/user-attachments/assets/bba5b427-d5b7-4ce5-9635-575a4402d61c" />


### Step 3

Navigate to your user profile.
<img width="1111" height="872" alt="image" src="https://github.com/user-attachments/assets/d469a368-4020-4f65-add3-c789bfbbfb69" />


### Step 4

Open the **API Key** section.

### Step 5

Copy your personal API key.

> **Important:** Never publish your actual API key in screenshots or public repositories. Blur or mask the key before uploading screenshots.

---

## Outcome

After completing this step, a valid VirusTotal API key is available for configuring the Wazuh Manager.

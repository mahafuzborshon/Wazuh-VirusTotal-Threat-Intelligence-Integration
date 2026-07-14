# Create a VirusTotal API Key

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

### Step 2

Create a free account or sign in to your existing account.

### Step 3

Navigate to your user profile.

### Step 4

Open the **API Key** section.

### Step 5

Copy your personal API key.

> **Important:** Never publish your actual API key in screenshots or public repositories. Blur or mask the key before uploading screenshots.

---

## Outcome

After completing this step, a valid VirusTotal API key is available for configuring the Wazuh Manager.

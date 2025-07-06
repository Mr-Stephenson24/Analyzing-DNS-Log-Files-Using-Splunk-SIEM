# Analyzing-DNS-Log-Files-Using-Splunk-SIEM

Introduction
DNS (Domain Name System) logs are crucial for understanding network activity and identifying potential security threats. Splunk SIEM (Security Information and Event Management) provides powerful capabilities for analyzing DNS logs and detecting anomalies or malicious activities.

Prerequisites
Before analyzing DNS logs in Splunk, ensure the following:

Splunk instance is installed and configured.
DNS log data sources are configured to forward logs to Splunk.


https://github.com/Mr-Stephenson24/Analyzing-DNS-Log-Files-Using-Splunk-SIEM/blob/main/Screenshot%202025-07-06%20092717.png?raw=true


https://github.com/Mr-Stephenson24/Analyzing-DNS-Log-Files-Using-Splunk-SIEM/blob/main/Screenshot%202025-07-06%20092717.png?raw=true

# Steps to Upload Sample DNS Log Files to Splunk SIEM

1. Prepare Sample DNS Log Files
Obtain sample DNS log file in a suitable format (e.g., text files).
Ensure the log files contain relevant DNS events, including source IP, destination IP, domain name, query type, response code, etc.
Save the sample log files in a directory accessible by the Splunk instance.
2. Upload Log Files to Splunk
Log in to the Splunk web interface.
Navigate to Settings > Add Data.
Select Upload as the data input method.
3. Choose File
Click on Select File and choose the sample DNS log file you prepared earlier.
4. Set Source Type
In the Set Source Type section, specify the source type for the uploaded log file.
Choose the appropriate source type for DNS logs (e.g., dns or a custom source type if applicable).
5. Review Settings
Review other settings such as index, host, and sourcetype.
Ensure the settings are configured correctly to match the sample DNS log file.
6. Click Upload
Once all settings are configured, click on the Review button.
Review the settings one final time to ensure accuracy.
Click Submit to upload the sample DNS log file to Splunk.
7. Verify Upload
After uploading, navigate to the search bar in the Splunk interface.

Run a search query to verify that the uploaded DNS events are visible.

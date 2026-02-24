# Event ID 4625: Brute Force Detection

## Attack Simulation
runas /user:wrongpassword123 cmd  (x3 failures)

## SOC Analyst Workflow
**Terminal → Event Viewer → Right-click → "Filter Current Log" → Event ID: 4625**

**Results:** Multiple Event ID 4625 failure audits in rapid succession (20:55 PM)

## Triage Analysis

**Production Splunk Query:**

index=windows EventCode=4625 | stats count by src_ip | sort -count

<img width="1920" height="1080" alt="Screenshot 2026-02-21 at 8 59 39 PM" src="https://github.com/user-attachments/assets/96c18d55-92a5-4e03-9bd3-c92c7406d9f7" />

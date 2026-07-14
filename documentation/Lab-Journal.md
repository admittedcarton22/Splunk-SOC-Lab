# Lab Journal

---

## Day 1 — July 12, 2026

### Goal
Build the foundation for a home SOC lab using Windows Server 2022, VirtualBox, and Splunk Enterprise.

### Completed
- Created the GitHub repository and project structure.
- Created project documentation and roadmap.
- Installed Oracle VirtualBox.
- Downloaded the Windows Server 2022 Evaluation ISO.
- Created and configured a Windows Server 2022 VM (6 GB RAM, 2 vCPUs, 80 GB disk).
- Installed Windows Server 2022 Desktop Experience.
- Renamed the server to **LAB-DC01**.
- Captured setup screenshots.

### Challenges
- VirtualBox displayed a black screen after reboot.
- Resolved by performing **Machine → Reset**.

### Next
- Install VirtualBox Guest Additions.
- Install Splunk Enterprise.

---

## Day 2 — July 13, 2026

### Goal

Improve VM usability and deploy Splunk for centralized log collection.

### Completed

- Installed VirtualBox Guest Additions.
- Enabled dynamic display resizing.
- Enabled shared clipboard.
- Improved mouse integration.
- Installed Splunk Enterprise.
- Created the Splunk administrator account.
- Verified the Splunk web interface (localhost:8000).
- Installed Splunk Universal Forwarder.
- Configured Splunk Enterprise to receive data on port 9997.
- Installed Sysmon with the SwiftOnSecurity configuration.
- Created `inputs.conf` to monitor the Sysmon Operational log.
- Restarted the Universal Forwarder.
- Verified Sysmon events were successfully ingested into Splunk.
- Captured installation and verification screenshots.

### Lessons Learned

- Guest Additions greatly improve VM usability.
- Splunk Enterprise provides a web interface on port 8000.
- Universal Forwarder collects and forwards Windows event logs.
- Sysmon provides detailed endpoint telemetry for security monitoring.
- Successful event ingestion confirms the logging pipeline is working.

### Next

- Build custom SPL searches.
- Create detection rules.
- Build security dashboards.
- Simulate Windows attacks and investigate the resulting events.

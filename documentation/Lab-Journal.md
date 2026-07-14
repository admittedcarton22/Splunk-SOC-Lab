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
Improve VM usability and deploy Splunk Enterprise.

### Completed
- Installed VirtualBox Guest Additions.
- Enabled dynamic display resizing.
- Enabled shared clipboard.
- Improved mouse integration.
- Installed Splunk Enterprise.
- Created the Splunk administrator account.
- Verified the Splunk web interface (`localhost:8000`).
- Logged into the Splunk dashboard.
- Captured installation screenshots.

### Lessons Learned
- Guest Additions greatly improve VM usability.
- Splunk Enterprise provides a web interface on port **8000**.

### Next
- Install Splunk Universal Forwarder.
- Install Sysmon.
- Configure log forwarding.
- Verify Windows Event Logs are ingested into Splunk.

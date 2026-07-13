# Lab Journal

## Day 1 — July 12, 2026

### Goal

Build the foundation for a home SOC lab using Windows Server 2022, VirtualBox, and Splunk Enterprise.

---

### Completed

- Created the Splunk-SOC-Lab GitHub repository.
- Designed the repository structure.
- Created project documentation.
- Created the lab roadmap.
- Installed Oracle VirtualBox.
- Downloaded the Windows Server 2022 Evaluation ISO.
- Created a Windows Server 2022 virtual machine.
- Configured the virtual machine (6 GB RAM, 2 vCPUs, 80 GB virtual disk).
- Installed Windows Server 2022 Desktop Experience.
- Renamed the server from the default hostname to **LAB-DC01**.
- Captured screenshots documenting each installation step.

---

### Challenges

**Issue**

After restarting the virtual machine to apply the hostname change, Windows Server displayed a black screen instead of booting normally.

**Troubleshooting**

Performed a **Machine → Reset** from VirtualBox.

**Result**

The virtual machine booted successfully, and the hostname **LAB-DC01** was retained.

---

### Lessons Learned

- VirtualBox may occasionally hang during a Windows Server reboot.
- A VirtualBox machine reset can resolve temporary boot issues without losing configuration changes.
- Enterprise systems should use descriptive hostnames rather than randomly generated default names.

---

### Next Objectives

- Install VirtualBox Guest Additions.
- Configure networking.
- Install Splunk Enterprise.
- Install Splunk Universal Forwarder.
- Install Sysmon.
- Verify Windows Event Log ingestion into Splunk.

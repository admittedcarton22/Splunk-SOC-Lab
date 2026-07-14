# Detect PowerShell Execution

## Purpose

Detect PowerShell execution using Sysmon events collected by Splunk.

## SPL Query

```spl
index=main PowerShell
```

## Result

Displays PowerShell execution events collected by Sysmon and indexed in Splunk. These events can be used to investigate PowerShell activity on the system.

## Screenshot

screenshots/06_spl_queries/28_detect_powershell.png

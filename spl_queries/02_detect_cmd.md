# Detect Command Prompt Execution

## Purpose

Detect Command Prompt (cmd.exe) execution using Sysmon events collected by Splunk.

## SPL Query

```spl
index=main cmd.exe
```

## Result

Displays Command Prompt execution events collected by Sysmon and indexed in Splunk. These events can be used to investigate command-line activity on the system.

## Screenshot

screenshots/06_spl_queries/29_detect_cmd.png

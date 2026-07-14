\# Detect PowerShell Execution



\## Purpose



Detect PowerShell execution using Sysmon Process Create events.



\## SPL Query



```spl

index=main PowerShell

```



\## Result



This query returns PowerShell execution events collected by Sysmon and forwarded to Splunk.



\## Screenshot



screenshots/06\_spl\_queries/28\_detect\_powershell.png


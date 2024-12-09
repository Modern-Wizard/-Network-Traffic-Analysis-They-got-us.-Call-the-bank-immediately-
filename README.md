# [Network Traffic Analysis] They got us. Call the bank immediately! 

## Based on the PowerShell logs investigation, we have seen the full impact of the attack:

    The threat actor was able to read and exfiltrate two potentially sensitive files.
    The domains and ports used for the network activity were discovered, including the tool used by the threat actor for exfiltration.

## Investigation Guide
Finally, we can complete the investigation by understanding the network traffic caused by the attack:

    Utilise the domains and ports discovered from the previous task.
    All commands executed by the attacker and all command outputs were logged and stored in the packet capture.
    Follow the streams of the notable commands discovered from PowerShell logs.
    Based on the PowerShell logs, we can retrieve the contents of the exfiltrated data by understanding how it was encoded and extracted.

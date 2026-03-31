# Suspicious PowerShell Activity Investigation

## Executive Summary

An alert was triggered for suspicious PowerShell activity on a host. Investigation showed the command was encoded and reached out to an external IP. This activity was determined to be malicious (True Positive).

## Environment

* Alert Source: EDR
* Host: Windows Workstation
* User: Employee

## Investigation Process

* Reviewed alert details
* Analyzed process tree
* Investigated command behavior
* Checked external IP

## Key Findings

* Encoded PowerShell command
* External IP connection

## Analysis

Encoded PowerShell commands are often used to hide malicious activity. The external connection supports this being malicious.

## Conclusion

* Verdict: True Positive
* Severity: High

## Response Actions

* Isolate host
* Block IP

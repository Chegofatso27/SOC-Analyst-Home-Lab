
# Investigation 001: Windows Audio Process Creation

## 1. Investigation Overview
Analysed a Windows process creation event collected using Microsoft Sysmon.

## 2. Event Information
- Event ID: 1 - Process Creation
- Date: 11 November 2026
- Process: audiodg.exe
- Parent Process: svchost.exe
- User: NT AUTHORITY\LOCAL SERVICE
- Integrity Level: System

## 3. Investigation Objective
To understand how Windows processes are created and how Sysmon records process activity.

## 4. Technical Analysis

### Process Name
audiodg.exe is a legitimate Windows component known as Windows Audio Device Graph Isolation. It handles audio processing.

### Process Location
C:\Windows\System32\audiodg.exe

The executable was located in the standard Windows System32 directory.

### Parent Process
svchost.exe

The recorded parent process was Windows Service Host, running under the LOCAL SERVICE account.

### User Context
NT AUTHORITY\LOCAL SERVICE

This is a built-in Windows service account.

## 5. Findings
The process location, executable name and parent process were consistent with expected Windows activity.

No immediate indicators of malicious activity were identified from the event details reviewed.

## 6. Conclusion
This investigation provided practical experience in analysing Sysmon Event ID 1, identifying parent and child processes, and interpreting Windows process execution information.

Further validation, including checking the executable's digital signature and hash reputation, would strengthen the assessment.

## 7. Skills Demonstrated
- Windows event log analysis
- Process investigation
- Parent-child process analysis
- Understanding Windows service accounts
- Basic threat assessment
- Security incident documentation


# Project 1: Windows Security Monitoring with Sysmon

## 1. Project Overview
This project documents the installation and use of Microsoft Sysmon to monitor Windows endpoint activity and investigate process creation events.

## 2. Lab Environment
- Operating System: Windows 10 64-bit
- Processor: Intel Core i7-1165G7
- RAM: 8 GB
- Monitoring Tool: Microsoft Sysmon 15.22
- Log Analysis Tool: Windows Event Viewer

## 3. Objective
To gain practical experience in endpoint monitoring, Windows event logging and basic security investigations.

## 4. Installation
Downloaded Microsoft Sysmon from the official Microsoft Sysinternals website.

Installed Sysmon using Command Prompt with administrator privileges.

Installation command:

    Sysmon64.exe -accepteula -i

## 5. Installation Verification
Confirmed that:
- Sysmon was installed successfully.
- SysmonDrv was installed and started.
- Sysmon64 service started successfully.

## 6. Log Collection
Accessed Sysmon logs through:

Applications and Services Logs > Microsoft > Windows > Sysmon > Operational

## 7. Event Investigated
- Event ID 1: Process Creation

## 8. Skills Practised
- Windows endpoint monitoring
- Sysmon installation
- Event Viewer navigation
- Process creation analysis
- Basic security investigation
- Security documentation

## 9. Conclusion
This project provided hands-on experience with Microsoft Sysmon and introduced me to collecting and analysing Windows process creation events as part of a SOC Analyst investigation workflow.

## 10. Future Improvements
- Investigate additional Sysmon event IDs.
- Configure an advanced Sysmon configuration.
- Practise identifying suspicious process behaviour.
- Integrate endpoint logs with a SIEM platform.

Incident Report 1 – Brute Force Attack
Incident Title

Brute Force Attack Detection on Windows Machine

Date of Incident

(Write the date when you performed the test)

Reported By

Nitesh Vishwakarma

Lab Environment

SOC Home Lab Environment

Tools Used:

Splunk

Wazuh

Kali Linux

Windows 10 Virtual Machine

Incident Summary

A suspicious activity was detected in the SOC lab environment where multiple failed login attempts were recorded on the Windows machine. The activity was identified as a potential brute-force attack initiated from the attacker machine.

The SIEM system generated an alert after detecting abnormal login behavior.

Incident Details

Attack Type:
Brute Force Login Attempt

Source Machine:
Kali Linux

Target Machine:
Windows 10

Detection Method:
Security logs and authentication failure events detected in Splunk SIEM.

Log Evidence:
Multiple failed login attempts within a short time period.

Example Log Event:
Failed login attempts detected from attacker IP address.

Investigation Process

Step 1:
Alert triggered in Splunk dashboard.

Step 2:
Checked Windows security event logs.

Step 3:
Identified repeated login failures.

Step 4:
Verified source IP address from attacker machine.

Step 5:
Confirmed brute force simulation from Kali Linux.

Impact Analysis

No real damage occurred because the environment is a controlled SOC lab setup.

However, in real-world environments this attack could:

Lead to unauthorized access

Compromise sensitive data

Allow attacker system control.

Mitigation Actions

The following actions were recommended:

Enable account lockout policy

Implement strong password policy

Monitor login attempts

Enable multi-factor authentication

Block suspicious IP addresses.

Lessons Learned

This project helped in understanding:

How brute force attacks work

How SIEM tools detect threats

How SOC analysts investigate incidents

Importance of log monitoring.

Attachments

Include screenshots of:

Splunk alert dashboard

Failed login logs

Attack simulation

Lab architecture diagram.

Analyst

Nitesh Vishwakarma
Aspiring SOC Analyst
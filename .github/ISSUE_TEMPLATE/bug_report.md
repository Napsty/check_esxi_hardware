---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

**Before actually creating a new issue**
I confirm, I have read the FAQ (https://www.claudiokuenzler.com/blog/308/check-esxi-hardware-faq-frequently-asked-questions): Y/N
I confirm, I have restarted the CIM server (` /etc/init.d/sfcbd-watchdog restart `) on the ESXi server and the problem remains: Y/N
I confirm, I have cleared the server's local IPMI cache (`localcli hardware ipmi sel clear`) and restarted the services (`/sbin/services.sh restart`) on the ESXi server and the problem remains: Y/N

**Describe the bug**
A clear and concise description of what the bug is. 

**Show the full plugin output, including the command with -V parameter**
Run the plugin with `-V` parameter and show the full output (including command) here. Obviously obfuscate credentials.

**Expected behavior**
A clear and concise description of what you expected to happen.

**Versions:**
 - check_esxi_hardware plugin: 
 - VMware ESXi:
 - pywbem: 
 - Python:
 - Third party tools (Dell OMSA, HP Offline Bundle, etc): 

**Additional context**
Add any other context about the problem here.

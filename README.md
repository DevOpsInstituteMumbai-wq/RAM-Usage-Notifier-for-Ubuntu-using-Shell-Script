**Problem Statement: RAM Usage Notifier for Ubuntu**

**Background**
System administrators often need to monitor RAM usage to ensure optimal performance and prevent system crashes due to high memory consumption. A RAM usage notifier script is required to track memory utilization and send an email alert when usage exceeds a predefined threshold.

**Challenges to Address**
Automated RAM Usage Monitoring


The threshold percentage (e.g., 80%) should be configurable.

**Email Notification System**

If RAM usage exceeds the threshold, an email alert should be sent to a specified recipient.

The email should include current RAM usage details and a timestamp.

Use mailx or sendmail for sending notifications.

**Automation & Execution**

The script should be executable using chmod a+x script.sh.

It should be scheduled via cron to run periodically (e.g., every 5 minutes).

**Expected Outcome**
A Bash script that:
✅ Monitors RAM usage on an Ubuntu system.
✅ Sends an email notification when usage exceeds the threshold.
✅ Can be scheduled for periodic execution using cron.

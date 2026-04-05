# Task 4 - Log Sources and Ingestion

## Log Sources

Every device in a network creates logs.

These logs show system and user activity.

---

## Windows Logs

Windows uses Event Viewer.

Each event has an Event ID.

This helps analysts track activity.

---

## Linux Logs

Common log locations:

* /var/log/httpd → HTTP logs
* /var/log/auth.log → Authentication logs
* /var/log/cron → Scheduled jobs
* /var/log/kern → Kernel logs

---

## Web Server Logs

Web servers store logs for all requests.

Example:

* User visits a website
* Server records the request

---

## Log Ingestion Methods

### 1. Agent / Forwarder

Installed on the device to send logs to SIEM.

---

### 2. Syslog

A protocol used to send logs to SIEM.

---

### 3. Manual Upload

Upload logs manually for analysis.

---

### 4. Port Forwarding

Devices send logs to a specific port.

---

## Key Point

SIEM collects logs using different methods and prepares them for analysis.

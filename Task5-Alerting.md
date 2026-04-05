# Task 5 - Alerting Process and Analysis

## Detection Rules

SIEM uses rules to detect threats.

These rules are based on conditions.

---

## Example Rules

* 5 failed logins → Alert
* Successful login after failures → Alert
* USB device connected → Alert

---

## Important Event IDs

* Event ID 104 → Logs deleted
* Event ID 4688 → Process execution

---

## Alert Types

### False Positive

* Not a real threat
* Needs rule tuning

### True Positive

* Real attack
* Needs investigation

---

## Alert Investigation Steps

1. Check the alert
2. Analyze related logs
3. Identify the cause
4. Take action

---

## Possible Actions

* Ignore (False Positive)
* Investigate more
* Contact user
* Isolate system
* Block IP

---

## Key Point

Good alert analysis helps detect real threats and reduce false alerts.

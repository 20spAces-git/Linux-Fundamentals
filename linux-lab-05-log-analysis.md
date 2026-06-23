# Linux Lab 05 - Log Analysis

## Objective

Learn how to locate, view, and analyze Linux log files using common command-line tools.

---

## Lab Environment

### Platform

- TryHackMe Linux Fundamentals Room
- Linux Terminal

### Commands Used

- ls
- cd
- cat
- less
- grep

---

## Procedure

### Step 1 - Navigate to Log Directory

Command:

cd /var/log

Purpose:

Access the primary Linux log directory.

---

### Step 2 - View Available Log Files

Command:

ls

Purpose:

Display available log files.

Common logs include:

- auth.log
- syslog
- kern.log

---

### Step 3 - View Log Contents

Command:

cat auth.log

Purpose:

Display the contents of a log file.

---

### Step 4 - Search for Specific Entries

Command:

grep "failed" auth.log

Purpose:

Locate failed login attempts.

---

### Step 5 - Review Logs Efficiently

Command:

less auth.log

Purpose:

Scroll through large log files.

Press:

q

to exit.

---

## Skills Practiced

- Log Analysis
- Event Investigation
- Evidence Collection
- Linux Navigation
- Pattern Searching

---

## What I Learned

Logs record important system events and activities.

Security analysts use logs to investigate incidents, identify suspicious activity, and reconstruct timelines.

---

## DFIR Relevance

Log files help investigators:

- Track login activity
- Identify failed authentication attempts
- Review system events
- Build timelines
- Investigate incidents

---

## Common Log Files

### auth.log

Authentication activity.

### syslog

General system activity.

### kern.log

Kernel-related events.

---

## Safety Considerations

- Avoid modifying log files.
- Review logs in read-only mode when possible.
- Preserve logs during investigations.

---

## Result

Successfully located and reviewed Linux log files using command-line tools.

Status: Completed ✅


🐧 Commands To Run
cd /var/log

ls

cat auth.log

grep "failed" auth.log

less auth.log

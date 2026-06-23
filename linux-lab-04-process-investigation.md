# Linux Lab 04 - Process Investigation

## Objective

Learn how to identify, monitor, and investigate running processes in Linux using common process management commands.

---

## Lab Environment

### Platform

- TryHackMe Linux Fundamentals Room
- Linux Terminal

### Commands Used

- ps
- ps aux
- top
- htop
- kill

---

## Procedure

### Step 1 - View Running Processes

Command:

ps

Purpose:

Displays processes associated with the current terminal session.

---

### Step 2 - View All Running Processes

Command:

ps aux

Purpose:

Displays all running processes on the system.

Information displayed includes:

- User
- Process ID (PID)
- CPU Usage
- Memory Usage
- Command

---

### Step 3 - Monitor System Activity

Command:

top

Purpose:

Displays real-time information about running processes and system resource usage.

Information includes:

- CPU Usage
- Memory Usage
- Running Processes
- System Load

---

### Step 4 - Review Process Information

Observe:

- Process Names
- Process IDs (PID)
- Resource Consumption
- User Ownership

---

### Step 5 - Terminate a Process

Command:

kill <PID>

Example:

kill 1234

Purpose:

Stops a running process using its Process ID.

---

## Skills Practiced

- Process Identification
- Process Monitoring
- Resource Analysis
- Process Termination
- System Investigation

---

## What I Learned

Linux uses processes to execute applications and system services.

Each process is assigned a unique Process ID (PID) that can be used to monitor or manage the process.

System administrators and security analysts regularly review running processes to understand system activity.

---

## DFIR Relevance

Process analysis helps investigators:

- Identify suspicious applications
- Detect unauthorized activity
- Investigate malware behavior
- Monitor resource consumption
- Perform incident response investigations

Running processes often provide valuable evidence during an investigation.

---

## Common Commands

### ps

Displays active processes.

### ps aux

Displays detailed information about all running processes.

### top

Displays real-time process activity.

### kill

Terminates a running process.

---

## Safety Considerations

- Verify the PID before terminating a process.
- Avoid stopping critical system processes.
- Review process ownership and purpose before taking action.

---

## Common Mistakes

### Killing the Wrong Process

Always verify the Process ID before using:

kill <PID>

Stopping the wrong process can cause applications or services to fail.

---

## Result

Successfully viewed, monitored, and investigated running Linux processes using common process management commands.

Status: Completed ✅

🐧 Commands To Run

In the Linux terminal:

ps

ps aux

top

If allowed in the environment:

htop

To exit top:

Press q

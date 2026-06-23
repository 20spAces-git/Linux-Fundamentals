# Linux Lab 02 - Permissions

## Objective

Learn how Linux file permissions work and how to view and modify permissions using common Linux commands.

---

## Lab Environment

### Platform

- TryHackMe Linux Fundamentals Room
- Linux Terminal

### Commands Used

- ls -l
- chmod
- chown

---

## Procedure

### Step 1 - Create a Test File

Command:

touch security.txt

Purpose:

Creates a file that will be used for permission testing.

---

### Step 2 - View File Permissions

Command:

ls -l

Purpose:

Displays file permissions, ownership, and file details.

Example Output:

-rw-r--r-- 1 user user 0 Jun 23 security.txt

---

### Step 3 - Modify Permissions

Command:

chmod 755 security.txt

Purpose:

Assigns read, write, and execute permissions to the owner while allowing read and execute permissions for others.

---

### Step 4 - Verify Permission Changes

Command:

ls -l

Purpose:

Confirms the permission changes were applied successfully.

Example Output:

-rwxr-xr-x 1 user user 0 Jun 23 security.txt

---

### Step 5 - Experiment with Different Permissions

Commands:

chmod 644 security.txt

chmod 600 security.txt

Purpose:

Observe how permissions change based on different values.

---

## Permission Breakdown

### 755

Owner:
- Read
- Write
- Execute

Group:
- Read
- Execute

Others:
- Read
- Execute

---

### 644

Owner:
- Read
- Write

Group:
- Read

Others:
- Read

---

### 600

Owner:
- Read
- Write

Group:
- No Access

Others:
- No Access

---

## Skills Practiced

- Permission Analysis
- Permission Modification
- File Security
- Access Control

---

## What I Learned

Linux permissions control who can access, modify, or execute files.

Proper permission management is critical for system security and preventing unauthorized access.

---

## DFIR Relevance

Permissions can reveal:

- Unauthorized changes
- Suspicious access
- Misconfigured systems
- Potential security risks

Investigators often review permissions during incident response activities.

---

## Safety Considerations

- Avoid granting excessive permissions.
- Follow the principle of least privilege.
- Verify permission changes before using sensitive files.

---

## Common Mistake

Using:

chmod 777 file.txt

This grants full permissions to everyone and can create security risks.

---

## Result

Successfully viewed and modified Linux file permissions using chmod and verified the changes with ls -l.

Status: Completed ✅



## commands to run
touch security.txt

ls -l

chmod 755 security.txt

ls -l

chmod 644 security.txt

ls -l

chmod 600 security.txt

ls -l

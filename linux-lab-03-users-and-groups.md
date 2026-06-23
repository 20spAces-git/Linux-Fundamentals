# Linux Lab 03 - Users and Groups

## Objective

Learn how Linux manages users and groups and how to identify account information using common Linux commands.

---

## Lab Environment

### Platform

- TryHackMe Linux Fundamentals Room
- Linux Terminal

### Commands Used

- whoami
- id
- groups
- sudo

---

## Procedure

### Step 1 - Identify Current User

Command:

whoami

Purpose:

Displays the username of the currently logged-in user.

---

### Step 2 - View User Information

Command:

id

Purpose:

Displays:

- User ID (UID)
- Group ID (GID)
- Group Memberships

---

### Step 3 - View Group Memberships

Command:

groups

Purpose:

Displays all groups associated with the current user.

---

### Step 4 - Review Sudo Usage

Command:

sudo -l

Purpose:

Displays commands the user is permitted to run with elevated privileges.

Note:
Results may vary depending on system configuration.

---

## Skills Practiced

- User Identification
- Group Analysis
- Privilege Awareness
- Linux Account Management

---

## What I Learned

Linux uses users and groups to control access to files, directories, and system resources.

Each user has a unique User ID (UID) and belongs to one or more groups.

---

## DFIR Relevance

Investigators often review:

- User Accounts
- Group Memberships
- Privilege Assignments
- Sudo Access

These items help determine:

- Who performed an action
- What permissions they had
- Whether unauthorized privilege escalation occurred

---

## Common Commands

### whoami

Displays the current username.

### id

Displays detailed account information.

### groups

Displays group memberships.

### sudo

Allows authorized users to execute commands with elevated privileges.

---

## Safety Considerations

- Follow the principle of least privilege.
- Only use sudo when necessary.
- Review account permissions regularly.

---

## Result

Successfully identified the current user, reviewed group memberships, and examined account privilege information.

Status: Completed ✅



## commands to run 
whoami

id

groups

sudo -l

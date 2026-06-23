# Linux Lab 01 - File Management

## Objective

Learn how to create, navigate, view, copy, move, and delete files and directories using Linux commands.

---

## Lab Environment

### Platform

- TryHackMe Linux Fundamentals Room
- Linux Terminal

### Commands Used

- pwd
- ls
- mkdir
- cd
- touch
- cp
- mv
- rm

---

## Procedure

### Step 1 - Display Current Directory

Command:

pwd

Purpose:

Displays the current working directory.

---

### Step 2 - List Directory Contents

Command:

ls

Purpose:

Displays files and directories within the current location.

---

### Step 3 - Create a New Directory

Command:

mkdir cyberlab

Purpose:

Creates a new directory named cyberlab.

---

### Step 4 - Enter the Directory

Command:

cd cyberlab

Purpose:

Moves into the newly created directory.

---

### Step 5 - Create a New File

Command:

touch notes.txt

Purpose:

Creates an empty file named notes.txt.

---

### Step 6 - Verify File Creation

Command:

ls

Purpose:

Confirms that notes.txt exists.

---

### Step 7 - Copy the File

Command:

cp notes.txt notes-copy.txt

Purpose:

Creates a duplicate copy of the original file.

---

### Step 8 - Rename the File

Command:

mv notes-copy.txt notes-final.txt

Purpose:

Renames the copied file.

---

### Step 9 - Delete the File

Command:

rm notes-final.txt

Purpose:

Removes the file from the directory.

---

### Step 10 - Verify Deletion

Command:

ls

Purpose:

Confirms the file was successfully removed.

---

## Skills Practiced

- File Creation
- Directory Creation
- Navigation
- File Copying
- File Renaming
- File Deletion

---

## What I Learned

Linux provides powerful command-line tools for managing files and directories.

Understanding file management commands is essential for system administration, cybersecurity investigations, and digital forensics.

---

## DFIR Relevance

Investigators frequently interact with:

- User files
- System files
- Evidence files
- Log files

Understanding how files are created, moved, copied, and deleted helps analysts reconstruct activity during investigations.

---

## Safety Considerations

- Verify file paths before deleting files.
- Use rm carefully because deleted files are not automatically recoverable.
- Confirm current directory with pwd before performing file operations.

---

## Result

Successfully created, copied, renamed, and deleted files using Linux commands.

Status: Completed ✅

# Day 6

Date: 6 June 2026

## Topics Learned

* Linux Users
* Linux Groups
* File Ownership
* chown Command
* Access Control Concepts
* Owner, Group and Others

## Commands Practiced

```bash
whoami
id
ls -l
cat /etc/group
chown
```

## Practical Work

* Checked current user information
* Viewed user and group IDs
* Examined file ownership
* Explored Linux groups
* Investigated how ownership affects file access

## Structure Created

```text
OwnershipLab
├── app.log
└── config.txt
```

## Concepts Learned

### User

A user is an account that can log in and perform actions on a Linux system.

### Group

A group is a collection of users that share permissions.

### Ownership

Every file and directory has:

```text
Owner
Group
```

Example:

```text
-rw-r--r-- suraj developers notes.txt
```

Meaning:

* Owner = suraj
* Group = developers

## Command Usage Examples

### Check Current User

```bash
whoami
```

### View User Information

```bash
id
```

### View Ownership

```bash
ls -l
```

### View Existing Groups

```bash
cat /etc/group
```

### Change Ownership

```bash
sudo chown username filename
```

### Change Owner and Group

```bash
sudo chown username:groupname filename
```

## What I Learned Today

* Linux uses users and groups for access management.
* Every file belongs to an owner and a group.
* Ownership directly affects file access.
* Groups simplify permission management.
* chown is used to change ownership.

## Cloud Relevance

* AWS EC2 servers use Linux user and group concepts.
* Application failures often occur because of incorrect ownership.
* Cloud Engineers manage ownership to secure systems.
* Understanding users and groups is essential before learning IAM in AWS.

## Hands-On Practice

* Checked current user identity.
* Investigated ownership of files.
* Viewed group information.
* Practiced reading ownership details from ls -l output.

## Troubleshooting Practice

* Investigated file access problems caused by ownership.
* Learned how ownership differs from permissions.
* Analyzed scenarios where applications could not modify files.

## Cloud Scenarios

### Scenario 1

Application runs as:

```text
appuser
```

But configuration file belongs to:

```text
root
```

Result:

Application cannot modify the file.

### Investigation

```bash
ls -l config.txt
```

Check:

* Owner
* Group
* Permissions

---

### Scenario 2

Developer says:

> I can read the file but cannot edit it.

Check:

```bash
ls -l filename
```

Verify ownership and write permissions.

## Interview Preparation

### Question

What is the difference between a user and a group?

### Answer

* User = Individual account.
* Group = Collection of users sharing permissions.

### Question

What does chown do?

### Answer

It changes file ownership.

### Question

Why are groups important?

### Answer

Groups make permission management easier by allowing multiple users to share access rights.

## Skills Gained

* Understanding Linux access control.
* Reading ownership information.
* Investigating ownership-related issues.
* Basic Linux administration concepts.

## Next Goal

Week 1 Revision and Linux Fundamentals Assessment.

```
```

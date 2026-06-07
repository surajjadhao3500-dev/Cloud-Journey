# Day 5

Date: 5 June 2026

## Topics Learned

* Linux Permissions
* Read, Write and Execute Permissions
* Permission Numbers (755, 777, 644)
* chmod Command
* Linux Security Basics

## Commands Practiced

```bash
chmod
whoami
id
ls -l
```

## Practical Work

* Viewed file permissions using `ls -l`
* Changed permissions using `chmod`
* Verified user information using `whoami`
* Checked user and group IDs using `id`
* Practiced different permission combinations

## Structure Created

```text
PermissionLab
├── project.txt
└── test.sh
```

## Permission Concepts Learned

### Read (r)

* View file contents

### Write (w)

* Modify file contents

### Execute (x)

* Run a file as a program

### Permission Examples

```text
755 = rwxr-xr-x
644 = rw-r--r--
777 = rwxrwxrwx
```

## Command Usage Examples

### Check Permissions

```bash
ls -l
```

### Change Permissions

```bash
chmod 755 project.txt
```

### Check Current User

```bash
whoami
```

### View User Details

```bash
id
```

## What I Learned Today

* Linux permissions control access to files and directories.
* Every file has Owner, Group, and Others permissions.
* chmod is used to modify permissions.
* Incorrect permissions can prevent applications from working properly.
* Permissions are a critical part of Linux security.

## Cloud Relevance

* Cloud Engineers manage permissions on Linux servers daily.
* Applications often fail because of incorrect permissions.
* AWS EC2 instances rely heavily on Linux permission concepts.
* Understanding permissions helps secure cloud infrastructure.

## Hands-On Practice

* Modified file permissions using chmod.
* Compared different permission values.
* Observed how permissions affect file access.
* Practiced reading Linux permission strings.

## Troubleshooting Practice

* Investigated why files could not be executed.
* Identified missing execute permissions.
* Learned how permission issues can break applications.

## Interview Preparation

### Question

What does permission 755 mean?

### Answer

* Owner: Read, Write, Execute
* Group: Read, Execute
* Others: Read, Execute

### Question

What is the difference between chmod and chown?

### Answer

* chmod changes permissions.
* chown changes ownership.

## Next Goal

Learn Linux users, groups, ownership, and access control concepts.

```
```

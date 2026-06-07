# Day 7

Date: 7 June 2026

## Topics Learned

* Week 1 Revision
* Linux Terminal Commands
* Linux File System
* File Management
* Permissions
* Users and Groups
* Ownership
* Basic Linux Troubleshooting

## Commands Revised

```bash
pwd
ls
ls -l
ls -a

cd
mkdir
touch
cat

cp
mv
rm

find
which

whoami
id

chmod
chown
```

## Practical Work

* Revised all Week 1 concepts
* Recreated Linux directory structures
* Practiced file management commands
* Reviewed permissions and ownership concepts
* Solved Linux troubleshooting scenarios

## Structure Created

```text
CloudJourney
├── Linux
│   ├── Day1
│   ├── Day2
│   ├── Day3
│   ├── Day4
│   ├── Day5
│   ├── Day6
│   └── Day7
└── AWS
```

## Week 1 Assessment Completed

### Tasks Performed

* Created directories and files
* Copied files using cp
* Renamed files using mv
* Deleted files using rm
* Located files using find
* Checked permissions using ls -l
* Verified user information using whoami and id
* Reviewed ownership concepts

## What I Learned This Week

### Linux Fundamentals

* Linux is the foundation of modern cloud infrastructure.
* Most cloud servers run Linux.
* Command-line skills are essential for Cloud Engineers.

### Navigation

* Navigating efficiently through directories.
* Understanding relative and absolute paths.

### File Management

* Creating, copying, moving, renaming and deleting files.
* Searching files using find.

### Permissions

* Read, Write and Execute permissions.
* Permission values like 755 and 644.
* Managing permissions using chmod.

### Users and Groups

* Understanding ownership.
* Managing access through users and groups.
* Using chown to change ownership.

## Cloud Relevance

* Linux is heavily used in AWS EC2 instances.
* Permissions protect applications and sensitive data.
* Ownership and access control are critical for server security.
* Troubleshooting Linux systems is a daily responsibility of Cloud Engineers.

## Hands-On Practice

* Repeated all important Linux commands.
* Solved permission-related scenarios.
* Solved ownership-related scenarios.
* Practiced troubleshooting using real-world examples.

## Troubleshooting Practice

### Scenario 1

Application cannot execute script.

Investigation:

```bash
ls -l script.sh
```

Solution:

* Check execute permissions.
* Add execute permission if required.

---

### Scenario 2

Developer cannot modify configuration file.

Investigation:

```bash
ls -l config.yml
```

Solution:

* Verify ownership.
* Verify write permissions.

---

### Scenario 3

File location unknown.

Investigation:

```bash
find . -name filename
```

Solution:

* Locate file before modifying it.

## Interview Preparation

### Question

What is the difference between chmod and chown?

### Answer

* chmod changes permissions.
* chown changes ownership.

### Question

What does 755 mean?

### Answer

```text
Owner  = rwx
Group  = r-x
Others = r-x
```

### Question

Why is Linux important for Cloud Engineers?

### Answer

Because most cloud servers, containers, and cloud-native platforms run on Linux.

## Week 1 Achievement

✅ Completed Linux Fundamentals Foundation

### Skills Gained

* Linux Navigation
* File Management
* File Searching
* Permissions Management
* Ownership Management
* Basic Troubleshooting
* Linux Administration Fundamentals

## Next Goal

Start Week 2:

* Processes
* PID
* ps
* top
* kill
* Services
* systemctl
* Logs
* Monitoring

## Progress Status

```text
Month 1: Linux Fundamentals
Week 1: Completed ✅
Week 2: Starting 🚀
```

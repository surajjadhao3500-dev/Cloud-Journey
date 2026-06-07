# Day 4

Date: 4 June 2026

## Topics Learned

* File Management in Linux
* Copying Files
* Moving Files
* Renaming Files
* Deleting Files
* Searching Files
* Locating Commands

## Commands Practiced

```bash
cp
mv
rm
find
which
```

## Practical Work

* Copied files using `cp`
* Renamed files using `mv`
* Moved files between directories
* Deleted files using `rm`
* Searched files using `find`
* Located command paths using `which`

## Structure Created

```text
FileManagementLab
├── Linux
├── AWS
└── Backup
```

## Command Usage Examples

### Copy File

```bash
cp notes.txt backup.txt
```

### Rename File

```bash
mv notes.txt day4.txt
```

### Move File

```bash
mv day4.txt Backup/
```

### Delete File

```bash
rm notes.txt
```

### Search File

```bash
find . -name notes.txt
```

### Locate Command

```bash
which ls
```

## What I Learned Today

* How to create backups using file copies.
* Difference between copying and moving files.
* Files deleted using `rm` are permanently removed.
* Linux provides powerful file search capabilities through `find`.
* Command locations can be identified using `which`.

## Cloud Relevance

* Cloud Engineers frequently back up configuration files before changes.
* Log files are often moved and archived for troubleshooting.
* Searching for configuration files is a common server administration task.
* Understanding command locations helps during troubleshooting and automation.

## Hands-On Practice

* Created file backups.
* Renamed project files.
* Moved files into different directories.
* Searched files from multiple locations.
* Verified command installation paths.

## Troubleshooting Practice

* Investigated missing files using `find`.
* Verified command locations using `which`.
* Practiced safe file management before deletion.
* Learned why backups are important before modifying production files.

## Next Goal

Learn Linux permissions, access control, and the chmod command.

```
```

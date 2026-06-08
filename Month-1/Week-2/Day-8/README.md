# Day 8

Date: 8 June 2026

## Topics Learned

- Linux Processes
- Process ID (PID)
- Foreground Processes
- Background Processes
- ps
- ps aux
- top
- kill

## Why Processes Matter

Every application running on Linux becomes a process.

Examples:

- Nginx
- Apache
- MySQL
- Docker
- Python Applications

Cloud Engineers use process management to identify performance issues and troubleshoot servers.

## Concepts Learned

### Process

A process is a running instance of a program.

Example:

Program → Chrome

Running Chrome → Process

### PID

PID stands for Process ID.

Each running process receives a unique identifier from Linux.

Example:

PID 1050

PID 2045

PID 3500

### Foreground Process

Runs directly in the terminal and occupies it until completion.

Example:

sleep 30

### Background Process

Runs independently without occupying the terminal.

Examples:

- Nginx
- MySQL
- Docker

## Commands Practiced

### ps

Displays running processes.

### ps aux

Displays detailed information about all running processes.

### top

Provides real-time monitoring of CPU, memory and processes.

### kill

Terminates a running process using its PID.

## Practical Work

- Viewed running processes
- Identified Process IDs
- Monitored CPU usage
- Monitored Memory usage
- Practiced process termination

## Cloud Scenarios

### Scenario 1

Website is down.

Investigation:

ps aux

Check whether:

- Nginx is running
- Apache is running
- Application process is running

### Scenario 2

Server is slow.

Investigation:

top

Check:

- CPU usage
- Memory usage
- Resource-consuming processes

## Interview Questions

### What is a Process?

A running instance of a program.

### What is PID?

A unique identifier assigned to a running process.

### What is the difference between a Program and a Process?

A program is stored on disk.

A process is executing in memory.

## What I Learned Today

- How Linux manages running programs
- Importance of PID
- Process monitoring using ps and top
- Process termination using kill
- Basic troubleshooting techniques

## Skills Gained

- Process Monitoring
- Process Management
- Linux Troubleshooting
- Resource Monitoring

## Next Goal

Learn Linux Services and systemctl.

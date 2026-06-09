# Day 9

Date: 9 June 2026

## Topics Learned

- Linux Services
- Daemons
- systemctl
- Service Status
- Starting Services
- Stopping Services
- Restarting Services
- Active and Inactive Services

## Commands Practiced

```bash
systemctl status ssh
sudo systemctl start ssh
sudo systemctl stop ssh
sudo systemctl restart ssh
systemctl list-units --type=service
```

## Practical Work

- Checked service status
- Viewed active services
- Identified service PIDs
- Observed service states
- Practiced service management commands

## What I Learned Today

- A service is a program that runs in the background.
- A daemon is a background process that provides services.
- Linux services are managed using systemctl.
- Services can be started, stopped, and restarted.
- Service status helps troubleshoot application issues.
- Most cloud applications depend on services.

## Cloud Relevance

- Nginx runs as a service.
- MySQL runs as a service.
- Docker runs as a service.
- SSH runs as a service.
- Cloud Engineers regularly manage services on EC2 instances.
- Service troubleshooting is a common cloud administration task.

## Skills Gained

- Service Monitoring
- Service Management
- Linux Administration
- Basic Troubleshooting
- Cloud Server Operations

## Next Goal

Learn Linux Logs and journalctl.

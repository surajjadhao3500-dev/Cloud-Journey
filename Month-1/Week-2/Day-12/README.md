# Day 12

Date: 12 June 2026

## Topics Learned

- Service Troubleshooting
- Service Failure Analysis
- Active Services
- Inactive Services
- Failed Services
- Service Recovery
- Service Logs
- Troubleshooting Workflow

## Commands Practiced

```bash
systemctl status ssh
systemctl --failed
sudo systemctl restart ssh
journalctl -u ssh
```

## Practical Work

- Checked service status
- Identified active and inactive services
- Viewed failed services
- Examined service logs
- Restarted services
- Verified service recovery

## What I Learned Today

- Service troubleshooting helps identify service-related issues.
- Services can be active, inactive, or failed.
- Failed services often require log analysis.
- systemctl is used to manage Linux services.
- journalctl helps investigate service problems.
- Service recovery is an important part of Linux administration.

## Cloud Relevance

- Web servers such as Nginx run as services.
- Databases such as MySQL run as services.
- Docker runs as a service.
- Cloud Engineers troubleshoot service failures regularly.
- AWS EC2 troubleshooting often involves service management.
- Service recovery helps restore application availability.

## Skills Gained

- Service Monitoring
- Service Management
- Service Recovery
- Log Analysis
- Linux Troubleshooting
## Next Goal

Learn System Monitoring and Resource Monitoring.

# Wazuh-n8n-Discord-Alerting

Automated SOC alerting pipeline integrating Wazuh SIEM, custom Python integrations, n8n workflow automation, and Discord notifications for real-time security event monitoring.

---

## Overview

This project demonstrates an automated security alerting pipeline that forwards Wazuh SIEM alerts to Discord using a custom Python integration and n8n workflow automation.

The system enables real-time incident notifications, helping SOC analysts respond quickly to suspicious activities and security events.

---

## Architecture

Wazuh Manager
↓
Custom Python Integration
↓
n8n Webhook
↓
Workflow Processing
↓
Discord Webhook
↓
Real-Time Alert Notification

---

## Features

- Real-time security alert forwarding
- Wazuh SIEM integration
- Custom Python integration script
- n8n workflow automation
- Discord webhook notifications
- JSON-based event processing
- Dockerized n8n deployment
- SOC analyst alerting pipeline

---

## Technologies Used

| Component | Technology |
|------------|------------|
| SIEM | Wazuh |
| Automation Platform | n8n |
| Notification Platform | Discord |
| Programming Language | Python |
| Communication | HTTP Webhooks |
| Containerization | Docker |
| Operating System | Linux |

---

## Project Structure

```text
Wazuh-n8n-Discord-Alerting/
│
├── screenshots/
│   ├── discord_alert_notification.png
│   ├── wazuh_ossec_directory.png
│   ├── custom_n8n_python_script.png
│   ├── n8n_workflow_execution.png
│   └── n8n_docker_container.png
│
├── custom-n8n.py
├── README.md
└── LICENSE
```

---

## Workflow

1. Wazuh detects a security event.
2. Custom Python integration extracts the alert.
3. Alert data is sent to an n8n webhook.
4. n8n processes the JSON payload.
5. The workflow forwards the event to Discord.
6. Analysts receive immediate notifications.

---

## Sample Alert

```json
{
  "rule": {
    "level": 12,
    "description": "SSH brute force attack"
  },
  "agent": {
    "name": "kali"
  }
}
```

---



---

## Use Cases

- Security Operations Center (SOC)
- Threat Detection
- Incident Response
- Alert Automation
- Blue Team Operations
- Detection Engineering

---

## Skills Demonstrated

- SIEM Administration
- Security Monitoring
- Detection Engineering
- Workflow Automation
- Python Scripting
- Docker
- Webhooks
- Incident Response
- SOC Operations

---

## Future Enhancements

- Microsoft Teams integration
- Slack notifications
- Email alerting
- Severity-based routing
- Threat intelligence enrichment
- Multi-channel notifications

---


---

## License

This project is released under the MIT License.

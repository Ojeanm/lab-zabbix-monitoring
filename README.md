⭐ Zabbix Monitoring Platform (lab)

📝 Overview

This repository documents the deployment and configuration of a Zabbix monitoring platform running in a Hyper-V homelab environment.

The platform provides centralized monitoring of infrastructure, including servers, services, containers, and network devices. It is designed to simulate a production-level monitoring environment for learning and experimentation.

🖥️ Environment

Virtualization Platform: Microsoft Hyper-V
Server OS: Ubuntu Server
Monitored Infrastructure:

Ubuntu Servers

Windows Server systems

Network infrastructure (VyOS, MikroTik CHR)

Containerized applications

⚙️ Platform Components

Zabbix Server – Central monitoring engine

Zabbix Agent – Installed on monitored hosts

Database Backend – Stores all monitoring data

Web Interface – Dashboard for visualization and alerting

📊 Monitoring Capabilities

The platform is configured to track:

✅ CPU utilization

✅ Memory usage

✅ Disk performance

✅ Service availability

✅ System uptime

✅ Network performance

It supports alerts and triggers to notify administrators when thresholds are exceeded.

🏗️ Architecture

The monitoring system follows a centralized architecture:

Zabbix server collects metrics from multiple hosts via agents

Data is stored in MySQL and visualized through the web dashboard

Alerts and notifications are configured for proactive monitoring




💻 Screenshots

Dashboard Overview



Host Monitoring Example



Alerts & Triggers



🎯 Skills Demonstrated

Infrastructure Monitoring & Observability

Centralized Metric Collection

Alerting & Notification Configuration

Linux Server Administration

Network and Host Monitoring

Documentation & Operational Playbooks

🚀 Future Enhancements

Monitor additional servers and services

Network device monitoring (switches, routers)

Alert integrations with Slack/email

Automated deployment scripts

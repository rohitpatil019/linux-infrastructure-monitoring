 # Linux Infrastructure Monitoring & Troubleshooting System

## Project Overview

Linux Infrastructure Monitoring & Troubleshooting System is a practical
Technical Support Engineer project developed to monitor and troubleshoot a
Linux-based server environment.

The project is deployed on an AWS EC2 instance running Linux. Apache HTTP
Server (`httpd`) is used as the web server, while Python is used to monitor
important system resources such as CPU, memory, and disk usage.

The project demonstrates practical IT Support activities including system
monitoring, service management, network troubleshooting, port checking, log
analysis, and server troubleshooting.

---

## Objective

The main objectives of this project are:

- Monitor Linux server health.
- Monitor CPU, memory, and disk usage.
- Monitor Apache HTTP Server (`httpd`).
- Check network connectivity.
- Monitor listening ports and services.
- Analyze system and Apache logs.
- Troubleshoot common server issues.
- Understand Linux service management.
- Automate basic monitoring activities.
- Develop practical Technical Support Engineer skills.

---

## Features

- Linux server monitoring
- CPU usage monitoring
- Memory usage monitoring
- Disk usage monitoring
- Apache HTTP Server (`httpd`) monitoring
- Network connectivity testing
- Port monitoring
- Service status monitoring
- Log file management
- Apache log analysis
- Server troubleshooting
- Python-based monitoring
- AWS EC2 deployment
- Basic monitoring automation

---

## Project Structure

```text
linux-infrastructure-monitoring/
│
├── scripts/
│   └── monitor.py
│
├── logs/
│   └── system.log
│
├── screenshots/
│   ├── 01
│   ├── 02
│   ├── 03
│   ├── 04
│   ├── 05
│   ├── 06
│   └── 07
│   └── 08
│
└── README.md

---

#Technologies Used
Technology
Purpose
Linux
Server operating system
AWS EC2
Cloud server
Python
System monitoring
Apache HTTP Server (httpd)
Web server
Bash
Linux administration
TCP/IP
Network communication
HTTP/HTTPS
Web communication
DNS
Name resolution
Cron
Monitoring automation

---

#Practical Task
The project involved setting up and managing a Linux server environment on AWS EC2 for practical Technical Support operations.
The Linux server was configured with Apache HTTP Server (httpd) and used as the primary web service. Python was implemented to monitor system resources including CPU usage, memory usage, disk usage, and server information.
Network troubleshooting activities were performed to verify connectivity, IP configuration, routing, DNS resolution, and listening ports.
Apache service management was also practiced by monitoring the service status, simulating service failure, restoring the service, and verifying web server availability.
System and Apache logs were analyzed to understand server events and identify possible issues.
The project also included basic monitoring automation and maintenance of monitoring logs.

---

#Practical Architecture
                         AWS Cloud
                            |
                            |
                     AWS EC2 Instance
                            |
                            |
                     Linux Server
                            |
              +-------------+-------------+
              |                           |
              |                           |
      Apache HTTP Server            Python Monitoring
            (httpd)                       |
              |                           |
           Port 80                +--------+--------+
              |                   |        |        |
              |                  CPU      RAM      Disk
              |
       Web Server
                                      |
                                      |
                                Monitoring Logs
                                      |
                                      |
                             Troubleshooting
                                      |
                         +------------+------------+
                         |            |            |
                      Network       Port        Service
                       Check        Check        Check

---


#Architecture Flow
User
  |
  v
Internet
  |
  v
AWS EC2
  |
  v
Linux Server
  |
  +---- Apache HTTP Server (httpd)
  |
  +---- Python Monitoring
  |
  +---- Network Monitoring
  |
  +---- Log Analysis
  |
  v
Troubleshooting & Resolution

---


#Learning Outcome
Through this project, I learned:
-linux server administration
-Linux command-line operations
-Apache HTTP Server (httpd) management
-AWS EC2 fundamentals
-CPU, memory, and disk monitoring
-Network troubleshooting
-IP addressing and routing basics
-Port and service troubleshooting
-System and Apache log analysis
-Python-based system monitoring
-Linux service management
-Basic monitoring automation
-Practical problem-solving
-Technical Support Engineer troubleshooting workflow
-Future Enhancements
-The project can be enhanced with:
-Email alerts for server problems
-CPU and memory threshold alerts
-Disk space alerts
-Web-based monitoring dashboard
-Real-time server monitoring
-multiple server monitoring
-Automated service recovery
-Database service monitoring
-AWS CloudWatch integration
-SMS or notification alerts
-Historical monitoring reports

---


#Author
Rohit Pradip Patil
Aspiring Technical Support Engineer
**GitHub:** https://github.com/rohitpatil019

**LinkedIn:** https://www.linkedin.com/in/rohit-patil-14166a278

---

#Skills Demonstrated
Linux
AWS EC2
Apache HTTP Server
Python
Networking
Troubleshooting
System Monitoring
Log Analysis

---

#Conclusion
The Linux Infrastructure Monitoring & Troubleshooting System provides practical experience in monitoring and maintaining a Linux server environment.
The project demonstrates how a Technical Support Engineer can monitor system resources, verify services, troubleshoot network and server problems, analyze logs, and restore services when issues occur.
This project helped me develop practical skills in Linux administration, Apache HTTP Server management, networking, troubleshooting, system monitoring, log analysis, and AWS EC2.

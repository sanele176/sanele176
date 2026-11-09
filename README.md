![Alternative Text](https://github.com/sanele176/Linux-Administration/blob/main/mindmap.png)


# IT Technical Specialist | Linux and Windows Systems | Infrastructure Monitoring | Automation** Portfolio

## Certifications

- MS-102: Microsoft 365 Certified: Administrator Expert
- MD-102: Microsoft 365 Certified: Endpoint Administrator Associate
- AZ-800: Administering Windows Server Hybrid Core Infrastructure
- MS-500: Microsoft 365 Certified: Security Administrator Associate
- SC-300: Identity and Access Administrator Associate
- SC-200: Security Operations Analyst Associate
- SC-900: Security, Compliance, and Identity Fundamentals
- LFS207: Linux System Administration Essentials (Linux Foundation)

## Repositories

| Repository | What it covers |
|---|---|
| [Linux-Administration](https://github.com/sanele176/Linux-Administration) | User and access control, LVM storage, package management, security hardening, Apache, Tomcat, NGINX, NFS, VSFTPD, chrony, and monitoring scripts |
| [Ansible](https://github.com/sanele176/Ansible) | Playbooks, roles, and inventory for automating infrastructure configuration |
| [Wazuh-SIEM](https://github.com/sanele176/Wazuh-SIEM) | Security monitoring and event analysis with Wazuh |
| [Exchange-Admin](https://github.com/sanele176/Exchange-Admin) | Exchange Online administration and PowerShell scripts |
| [portfolio](https://github.com/sanele176/portfolio) | Portfolio website source |
| [Microsoft-Intune-And-other-EUS-Tasks](https://github.com/sanele176/Microsoft-Intune-And-other-EUS-Tasks) | Intune and Autopilot deployment, BitLocker, Office and Visio packaging, printers, drivers, and end-user troubleshooting notes |
| [Linux-Administration/Monitoring](https://github.com/sanele176/Linux-Administration/tree/main/Monitoring) | Daily health-report scripts, Grafana, Prometheus, SolarWinds, Nagios, and Zabbix examples |

# Microsoft Intune and End-User Support Tasks

Practical notes and scripts for managing Windows endpoints with Microsoft Intune and related end-user support tasks.

## Contents

| Folder or file | What it covers |
|---|---|
| Auto Pilot | Windows Autopilot device registration and onboarding |
| Bitlocker | Drive encryption policy and recovery key handling |
| Deploy Office Apps | Deploying Microsoft 365 apps through Intune |
| Deploy Visio on Intune | Packaging and deploying Visio |
| Device Configuration/Windows | Windows device configuration profiles |
| Drivers | Driver deployment and troubleshooting |
| LocalAdminRights | Managing local administrator rights on endpoints |
| Printers | Printer deployment and configuration |
| XML Policy examples | Example policy files |
| Bulk uninstall apps via PowerShell | Removing applications across multiple devices |
| Install Wifi driver | Installing a wireless driver on a managed device |
| Scan windows | Windows scanning and related troubleshooting |

## Troubleshooting notes

- Files not deleting on SharePoint
- Intune image not updating
- Outlook issues
- Removing a language pack from Windows

## Notes

These are lab and procedure notes. They contain no client or employer data.

## Unix System Administration
[Check out My Unix Repo](https://github.com/sanele176/Linux-Administration)

### Core System Management
#### User Administration & Access Control
- Implementation and management of user accounts, groups, and privileges
- Sudo policy configuration and management
- Password policies and account security enforcement
- User quota management and monitoring
- ACL (Access Control List) implementation and management

#### Storage Management
- Design and implementation of complex storage solutions using Logical Volume Management (LVM)
- Experience with dynamic volume management:
  - Online volume expansion and reduction
  - Snapshot creation and management
  - Stripe and mirror configuration
- File system expertise:
  - XFS and EXT4 file system administration
  - File system tuning and optimization
  - Real-time monitoring and troubleshooting
- Partition management:
  - Complex partition mapping and creation
  - RAID configuration and management
  - Disk health monitoring and maintenance

#### Package Management
- Repository management (YUM/DNF/APT)
- Local repository creation and maintenance
- Package dependency resolution
- Custom package creation and modification
- Version control and rollback procedures
- Repository mirroring and synchronization

### Security & Hardening
- Implementation of security baseline configurations
- Firewall configuration (iptables/firewalld)
- Implementation of PAM modules for enhanced authentication
- SSL/TLS certificate management
- Security patch management and vulnerability assessment

### Access Control & Authentication

#### PowerBroker Identity Services (PBIS) Implementation

- Domain join and configuration
- Group policy integration
- User authentication and authorization
- Access control list management
- Local group policy configuration
- Home directory auto-creation
- Shell and login restrictions
- UID/GID mapping and management

### Network Services

#### Web Services
- Apache HTTPD configuration and optimization
  - Virtual host management
  - SSL/TLS implementation
  - Load balancing configuration
  - Module management and security hardening
- Tomcat application server administration
  - Performance tuning
  - Memory management
  - Application deployment
  - Clustering configuration
- NGINX deployment and configuration
  - Reverse proxy setup
  - Load balancing
  - Rate limiting
  - Cache optimization

#### File Services
- VSFTPD server configuration and management
  - Secure FTP implementation
  - User authentication and access control
  - Bandwidth throttling
  - Logging and monitoring
- NFS server implementation
  - Export configuration
  - Access control and security
  - Performance optimization
  - High availability setup

#### Network Infrastructure
- Time synchronization (chrony/NTP)
  - Stratum configuration
  - Time source management
  - Network time security

### Enterprise Integration
#### Active Directory Integration
- Implementation of AD authentication using:
  - PowerBroker Identity Services (PBIS)
  - Realmd and SSSD
- Group Policy Object (GPO) integration
- Single Sign-On (SSO) configuration
- Cross-platform identity management

### Automation & Monitoring
[More Details on](https://github.com/sanele176/Linux-Administration/tree/main/Monitoring)

#### Scripting & Automation
- Bash scripting for system administration tasks
  - System health monitoring
  - Backup automation
  - User management
  - Performance optimization
- Ansible automation
  - Playbook development
  - Role creation and management
  - Inventory management
  - Configuration management
 
## Contents

- **Daily health report.** A Bash script that collects CPU, memory, disk, and network metrics, sends the report by SMTP relay, and runs on a schedule through cron.
- **Grafana.** Dashboard creation, data source integration, and alert configuration. Screenshots come from a decommissioned cloud lab.
- **Prometheus.** Metric collection, query examples, Alertmanager configuration, and service discovery.
- **SolarWinds.** Network and server monitoring, capacity planning, and custom metrics.
- **Nagios.** Service checks, performance tracking, and alert configuration.
- **Zabbix.** Templates, triggers, and distributed monitoring.
- **Switch monitoring.** Example of monitoring a network switch.

#### Monitoring Solutions

- Bash script and SMTP Relay
   - Daily server health reports
   - Relayed to mail
   - scheduled via cron

![Alternative Text](https://github.com/sanele176/Linux-Administration/blob/main/Monitoring/Sample_automated_mail_daily_health_report.png)

- Grafana
  - Dashboard creation and customization
  - Data source integration
  - Alert configuration
  - Performance visualization
 
    (NOTE: Image from a decommissioned cloud lab environment)

![Alternative Text](https://github.com/sanele176/Linux-Administration/blob/main/Monitoring/prometheus_02.PNG)


- Prometheus
  - Metric collection and storage
  - Query optimization
  - Alert manager configuration
  - Service discovery
- SolarWinds
  - Network performance monitoring
  - Server & application monitoring
  - Capacity planning
  - Custom metric creation
- Nagios
  - Service monitoring
  - Performance tracking
  - Alert configuration
  - Plugin development
- Zabbix
  - Infrastructure monitoring
  - Template creation
  - Trigger configuration
  - Distributed monitoring
 
  ![Alternative Text](https://github.com/sanele176/Linux-Administration/blob/main/Switchmonitoring.png)

## Microsoft 365 & Azure Administration

### Exchange Online Management
- Mailbox administration
  - Creation and configuration of user mailboxes
  - Distribution group management
  - Resource mailbox setup
  - Mailbox permission management
- Storage management
  - Retention policy implementation
  - Archive mailbox configuration
  - eDiscovery management
  - Storage quota administration

### Azure Active Directory (Entra ID)
- Identity management
  - User lifecycle management
  - Group policy administration
  - Role-based access control (RBAC)
  - Conditional access policies
- Entra Connect implementation
  - Directory synchronization configuration
  - Password hash synchronization
  - Pass-through authentication
  - Federation services

### Security & Compliance
- Third-party application SSO integration
- Multi-factor authentication (MFA) implementation
- Conditional access policy management
- Security compliance monitoring
- Data loss prevention (DLP) configuration

### PowerShell Automation
- Exchange Online management scripts
- Azure AD automation
- Bulk user management
- Report generation
- Policy implementation

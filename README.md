![azure-security-banner](./img/azure-security-banner.jpg)

# Azure Security
Personal notes, walkthrough and insights for the SC-200: MS SecOps Analyst content.


## Topics covered

# Manage a security operations environment

### Configure settings in Microsoft Defender XDR
  * [Configure alert and vulnerability notification rules](./Configure%20alert%20and%20vulnerability%20notification%20rules.md)
  * Configure Microsoft Defender for Endpoint advanced features
  * Configure endpoint rules settings
  * Manage automated investigation and response capabilities in Microsoft Defender XDR
  * Configure automatic attack disruption in Microsoft Defender XDR

### Manage assets and environments
  * Configure and manage device groups, permissions, and automation levels in Microsoft Defender for Endpoint
  * Identify unmanaged devices in Microsoft Defender for Endpoint
  * Discover unprotected resources by using Defender for Cloud
  * Identify and remediate devices at risk by using Microsoft Defender Vulnerability Management
  * Mitigate risk by using Exposure Management in Microsoft Defender XDR

### Design and configure a Microsoft Sentinel workspace
 * Plan a Microsoft Sentinel workspace
 * Configure Microsoft Sentinel roles
 * Specify Azure RBAC roles for Microsoft Sentinel configuration
 * Design and configure Microsoft Sentinel data storage, including log types and log retention

### Ingest data sources in Microsoft Sentinel
 * Identify data sources to be ingested for Microsoft Sentinel
 *	Implement and use Content hub solutions
 *	Configure and use Microsoft connectors for Azure resources, including Azure Policy and diagnostic settings
 *	Plan and configure Syslog and Common Event Format (CEF) event collections
 *	Plan and configure collection of Windows Security events by using data collection rules, including Windows Event Forwarding (WEF)
 *	Create custom log tables in the workspace to store ingested data
 *	Monitor and optimize data ingestion

# Configure protections and detections

### Configure protections in Microsoft Defender security technologies
 * Configure policies for Microsoft Defender for Cloud Apps
 *	Configure policies for Microsoft Defender for Office 365
 *	Configure security policies for Microsoft Defender for Endpoints, including attack surface reduction (ASR) rules
 *	Configure cloud workload protections in Microsoft Defender for Cloud

### Configure detections in Microsoft Defender XDR
 *	Configure and manage custom detection rules
 *	Manage alerts, including tuning, suppression, and correlation
 *	Configure deception rules in Microsoft Defender XDR

### Configure detections in Microsoft Sentinel
 *	Classify and analyze data by using entities
 *	Configure and manage analytics rules
 *	Query Microsoft Sentinel data by using ASIM parsers
 *	Implement behavioral analytics

# Manage incident response

### Respond to alerts and incidents in the Microsoft Defender portal
 *	Investigate and remediate threats by using Microsoft Defender for Office 365
 *	Investigate and remediate ransomware and business email compromise incidents identified by automatic attack disruption
 *	Investigate and remediate compromised entities identified by Microsoft Purview data loss prevention (DLP) policies
 *	Investigate and remediate threats identified by Microsoft Purview insider risk policies
 *	Investigate and remediate alerts and incidents identified by Microsoft Defender for Cloud workload protections
 *	Investigate and remediate security risks identified by Microsoft Defender for Cloud Apps
 *	Investigate and remediate compromised identities that are identified by Microsoft Entra ID
 *	Investigate and remediate security alerts from Microsoft Defender for Identity

### Respond to alerts and incidents identified by Microsoft Defender for Endpoint
 *	Investigate device timelines
 *	Perform actions on the device, including live response and collecting investigation packages
 *	Perform evidence and entity investigation

### Investigate Microsoft 365 activities
 *	Investigate threats by using the unified audit log
 *	Investigate threats by using Content Search
 *	Investigate threats by using Microsoft Graph activity logs

### Respond to incidents in Microsoft Sentinel
 *	Investigate and remediate incidents in Microsoft Sentinel
 *	Create and configure automation rules
 *	Create and configure Microsoft Sentinel playbooks
 *	Run playbooks on on-premises resources

### Implement and use Microsoft Security Copilot
 *	Create and use promptbooks
 *	Manage sources for Security Copilot, including plugins and files
 *	Integrate Security Copilot by implementing connectors
 *	Manage permissions and roles in Security Copilot
 *	Monitor Security Copilot capacity and cost
 *	Identify threats and risks by using Security Copilot
 *	Investigate incidents by using Security Copilot

# Manage security threats

### Hunt for threats by using Microsoft Defender XDR
 *	Identify threats by using Kusto Query Language (KQL)
 *	Interpret threat analytics in the Microsoft Defender portal
 *	Create custom hunting queries by using KQL

### Hunt for threats by using Microsoft Sentinel
 *	Analyze attack vector coverage by using the MITRE ATT&CK matrix
 *	Manage and use threat indicators
 *	Create and manage hunts
 *	Create and monitor hunting queries
 *	Use hunting bookmarks for data investigations
 *	Retrieve and manage archived log data
 *	Create and manage search jobs

### Create and configure Microsoft Sentinel workbooks
 *	Activate and customize workbook templates
 *	Create custom workbooks that include KQL
 *	Configure visualizations

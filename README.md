# sentinel-splunk-siem-lab
## 🎬 Watch Me Build This Lab!

[![Watch the video](https://i.imgur.com/your-thumbnail.png)](https://www.loom.com/share/e8405fe2157c418d934710b748976e8f)

---

# Sentinel-Splunk-SIEM-Integration-Lab

### Description  
A hands-on cybersecurity lab demonstrating **Microsoft Sentinel** and **Splunk** integration for real-world **SIEM (Security Information and Event Management)** use cases. The project focuses on building detection analytics, visual dashboards, and understanding event correlation between cloud and on-prem sources.

---

## 🧠 Project Overview

This project simulates a **Security Operations Center (SOC)** workflow using both **Microsoft Sentinel (SIEM)** and **Splunk** to monitor, detect, and analyze threats in a hybrid environment.  

The goal was to:  
- Create and configure workspaces in **Sentinel** and **Splunk**  
- Connect event sources to both platforms for log ingestion  
- Build **custom detection rules** and **dashboards** to visualize security activity  
- Compare incident investigation and response capabilities between the two tools  

---

## 🧩 Tools & Technologies Used

| Category | Tool / Service |
|-----------|----------------|
| SIEM | Microsoft Sentinel |
| Log Management | Splunk Enterprise |
| Cloud Platform | Microsoft Azure |
| Data Source | Security logs, simulated events |
| OS | Windows 11 / Azure VM |
| Scripting | KQL (Kusto Query Language) |

---

## ⚙️ Project Steps

### Step 1: Environment Setup  
1. Deployed an **Azure Virtual Machine** for a Windows environment.  
2. Installed and configured **Splunk Enterprise** locally for log collection.  
3. Connected **Microsoft Sentinel** to Azure Log Analytics Workspace.  

### Step 2: Data Source Integration  
1. Ingested system and security event logs into both Sentinel and Splunk.  
2. Verified data flow using **KQL queries** and **Splunk Search Processing Language (SPL)**.  
3. Tested ingestion with sample login and alert events.

### Step 3: Detection & Analytics  
1. Created **analytic rules in Microsoft Sentinel** to detect failed logins and suspicious authentication behavior.  
2. Built **dashboards in Splunk** visualizing login activity and network anomalies.  
3. Compared **alert correlation** between Sentinel and Splunk for incident triage.

### Step 4: Incident Investigation  
1. Used **Sentinel’s Investigation Graph** to trace attack paths and user behaviors.  
2. Tested **Splunk Incident Review** to prioritize events and assign ownership.  
3. Documented findings, comparing efficiency and visualization between both SIEMs.

---

## 📊 Key Learnings

- Enhanced understanding of **SIEM fundamentals** and **log correlation**.  
- Developed skills in **Microsoft Sentinel analytics, KQL, and workbook dashboards**.  
- Improved familiarity with **Splunk SPL searches** and **alerting workflows**.  
- Strengthened ability to compare and evaluate **SOC tool performance** in hybrid environments.  

---

## 💡 Next Steps

- Integrate **Microsoft Defender for Endpoint** as an EDR data source.  
- Add **Logic Apps automation** for incident response in Sentinel.  
- Extend Splunk inputs for network and firewall data for broader visibility.  

---

## 🔗 Resources
- [Microsoft Sentinel Documentation](https://learn.microsoft.com/en-us/azure/sentinel/)  
- [Splunk Security Documentation](https://docs.splunk.com/Documentation/Splunk/latest/Security/About)  
- [KQL Query Language](https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/)

---

## 🧰 Repository Structure

---

## 🧾 Commit Message Example
> Initial project documentation with Sentinel and Splunk integration steps, screenshots, and Loom walkthrough.

---



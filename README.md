
[Watch the video](https://www.loom.com/share/e8405fe2157c418d934710b748976e8f)



<img width="1638" height="845" alt="thumnail" src="https://github.com/user-attachments/assets/7113476d-63b8-4009-a8e9-72dde5e44539" />


# 🎬 Splunk + Sentinel Lab

## Project Overview
This lab demonstrates a practical SOC workflow using **Splunk** and **Microsoft Sentinel**.  
In Splunk, synthetic process activity (like PowerShell commands and malware-style downloads) is generated and visualized on a KPI dashboard.  
In Microsoft Sentinel, a scheduled **analytic alert** is created to detect spikes in failed sign-ins, simulating a common brute-force scenario.  
This project highlights end-to-end SIEM ingestion, detection, and alerting, showcasing hands-on **log analysis, KQL, dashboards, and automated alert rules**.

---


## 🛠 Tools & Technologies
- **SIEM:** Microsoft Sentinel, Splunk  
- **Cloud:** Azure Portal & Log Analytics  
- **Security & Detection:** KQL, automated analytic alerts  
- **Operating Systems:** Windows 11


## ⚡ Key Steps Demonstrated
1. **Splunk Synthetic Event Generation**  
   - Simulate suspicious process activity (encoded PowerShell, malware-style downloads).  
   - Filter and aggregate events using SPL queries.  
   - Visualize total detections as a KPI panel on a dashboard.


2. **Dashboard Setup in Splunk**  
   - Create a dashboard panel titled “Suspicious Execution Overview.”  
   - Pin panel to a SOC-style dashboard for ongoing monitoring.


3. **Microsoft Sentinel Analytic Rule**  
   - Query authentication logs for failed sign-ins using KQL.  
   - Create a scheduled analytic rule (runs every 10 minutes) to trigger alerts for excessive failed login attempts.  
   - Verify alert rule activation and ensure automated detection works as intended.


 ## 🔑 Skills Demonstrated
 - Log analysis and detection in Splunk  
 - KQL query writing and log analytics in Microsoft Sentinel  
 - Scheduled alert creation and SOC-style workflow implementation  
 - Dashboard visualization for real-time monitoring  




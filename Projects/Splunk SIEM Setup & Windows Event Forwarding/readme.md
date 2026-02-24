<p align="center">
  <img src="banner.png" alt="Splunk SIEM Setup Banner" width="100%">
</p>

# Splunk SIEM Setup & Windows Event Forwarding
*A hands-on enterprise SIEM deployment project using Splunk Enterprise and Universal Forwarders.*

---

## Download the Full Project PDF
For a polished, portfolio-quality version of this project with diagrams and explanations:

 **[Download PDF](./Splunk-SIEM-Setup.pdf)**

---

## Project Overview
This project demonstrates the deployment and configuration of a functioning **Security Information and Event Management (SIEM)** architecture using **Splunk Enterprise** on a Debian server and **Windows Universal Forwarders** across domain clients.

The work includes:
- Installing Splunk Enterprise (Indexer + Search Head)
- Installing and configuring Universal Forwarders
- Creating a custom Windows Event Log index
- Querying forwarded logs in real time
- Analyzing Windows Event ID data to validate host activity

This environment replicates a real SOC workflow and shows competency in log aggregation, SIEM configuration, and enterprise monitoring.

---

## Architecture Diagram
<p align="center">
  <img src="./screenshots/network-diagram.png" alt="SIEM Network Diagram" width="80%">
</p>

---

## 📸 Key Screenshots

### 🔹 Splunk Enterprise Web Interface  
<p align="center">
  <img src="./screenshots/splunk-ui.png" alt="Splunk UI Screenshot" width="80%">
</p>

### 🔹 Universal Forwarder Running on Windows  
<p align="center">
  <img src="./screenshots/forwarder.png" alt="Universal Forwarder Screenshot" width="80%">
</p>

### 🔹 Querying Windows Event Logs  
<p align="center">
  <img src="./screenshots/event-search.png" alt="Windows Event Search" width="80%">
</p>

---

## Tools & Technologies
- Splunk Enterprise 10.x  
- Splunk Universal Forwarder  
- Debian Linux Server  
- Windows Event Logs  
- Custom Splunk Index Configuration  
- SIEM Log Forwarding Architecture  

---

## Summary of Findings
A sample Windows event received from the Universal Forwarder:

- **EventCode:** 16394  
- **Meaning:** The "Software Protection Platform Service" has successfully started.  
- **Relevance:** Confirms that host application logs are correctly forwarded, indexed, and searchable.

This validates the SIEM pipeline end-to-end.

---

## Key Learning Outcomes
- Built practical SIEM ingestion workflows  
- Gained experience with Universal Forwarder configuration  
- Configured custom indexes and receiving ports  
- Performed Windows Event Log triage using Splunk Search  
- Strengthened understanding of enterprise log architecture and SOC workflows  

---
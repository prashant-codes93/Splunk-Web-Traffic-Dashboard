# Splunk Web Traffic Security Dashboard

A SOC-focused Splunk project for monitoring, analyzing, and investigating web traffic logs using SPL (Search Processing Language).

## 📌 Project Overview

This project demonstrates how web access logs can be collected, ingested into Splunk, analyzed using SPL queries, and visualized through a security-focused dashboard.

The project is designed from a SOC Analyst perspective to identify normal web traffic as well as potentially suspicious activities such as high-volume requests, excessive HTTP errors, suspicious URL access, unusual HTTP methods, and possible scanning behavior.

---

## 🎯 Objectives

- Ingest web traffic logs into Splunk
- Create and configure a dedicated Splunk index
- Extract important fields from raw web access logs
- Analyze HTTP request activity using SPL
- Investigate source IP behavior
- Monitor HTTP status codes
- Identify suspicious URL requests
- Detect abnormal web traffic patterns
- Create a SOC-style security dashboard
- Practice web traffic investigation using Splunk

---

## 🛠️ Technologies Used

- Splunk
- SPL (Search Processing Language)
- Kali Linux
- Windows
- Web Access Logs
- Git
- GitHub

---

## 🔧 Splunk Configuration

### Index

```text
web_traffic

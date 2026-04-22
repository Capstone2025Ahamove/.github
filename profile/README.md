# Ahamove KPI Analytics & AI Dashboard System

## Overview
This capstone project develops a **Balanced Scorecard (BSC)-based analytics platform** for Ahamove, a leading on-demand logistics company in Vietnam. The system standardizes KPI tracking across multiple departments and provides real-time insights through dashboards and AI-powered analysis.

The solution integrates:
- Business Intelligence dashboards (Power BI)
- Automated data pipelines
- AI-powered KPI analysis via mobile applications

---

## Problem Statement
Ahamove faced challenges with:
- Fragmented KPI definitions across departments
- Manual reporting using spreadsheets
- Delayed insights due to disconnected data sources

This project addresses these issues by creating a **centralized, data-driven performance monitoring system**.

---

## Key Features

### 📊 KPI Analytics Platform
- Standardized KPI dictionary across 7 departments
- Real-time dashboards using Power BI
- Automated data pipelines (CSV → SQL/API transition)

### 🤖 AI-Powered Insights
- KPI forecasting using machine learning models
- Anomaly detection for early warning signals
- Predictive analytics integrated into dashboards

### 📱 Mobile Application (iOS)
- Upload dashboard images or Excel/CSV files
- AI-driven analysis and automated summaries
- Interactive chat interface for querying insights
- Persistent storage of analysis and conversations

---

## Architecture
Data Sources → ETL Pipeline → Power BI Dashboards  
↓  
AI/ML Module  
↓  
Mobile Applications (iOS/Android)  

---

## Technologies Used

### Data & BI
- Power BI
- SQL / API-based data pipelines
- ETL (Power Query)

### Machine Learning
- Regression models (forecasting KPIs)
- Time-series prediction (RNN / LSTM concepts)
- Anomaly detection (Power BI)

### Mobile Development
- SwiftUI (iOS)
- File upload & data processing
- AI integration for analysis

### System Design
- Balanced Scorecard (BSC)
- KPI governance framework
- Data pipeline automation

---

## Team Contributions

Code Commanders – RMIT University Capstone Project (2025)  
A cross-functional team collaborated to deliver an end-to-end KPI analytics system, covering data pipelines, dashboards, AI modeling, and mobile applications.

- **Le Trung Kien (Mobile & Integration)** – Built iOS app with SwiftUI and implemented AI-driven KPI analysis workflows  
- **Dang Vinh Luan (Data & BI Lead)** – Designed KPI framework and developed Power BI dashboards and data models  
- **Pham Nguyen Minh Dang (Data Engineering)** – Developed ETL processes, data transformations, and dashboard validation  
- **Luu Tuan An (AI/ML & System Design)** – Designed and implemented machine learning models for forecasting and anomaly detection  

Collaborated on system architecture, client communication, and aligning technical implementation with business needs.

---

## Results & Impact

- Enabled **real-time KPI monitoring** across 7 departments  
- Improved data accessibility and reduced manual reporting effort  
- Introduced **predictive analytics for proactive decision-making**  
- Delivered a production-ready system for demonstration and stakeholder use  

---

## Screenshots

<table>
<tr>
<td align="center">
<img width="250" alt="Picture1" src="https://github.com/user-attachments/assets/dda2ea20-a67a-45a7-acd5-fa2144d3cd99" />
<br/>
<b>Home / Upload</b>
</td>

<td align="center">
<img width="250" alt="Picture2" src="https://github.com/user-attachments/assets/325cc94a-2c0d-41f5-bd35-784fa70e1c70" />
<br/>
<b>KPI Prediction</b>
</td>

<td align="center">
<img width="250" alt="Picture3" src="https://github.com/user-attachments/assets/55ce7a5b-10d8-4d3f-8e1a-6aba9e9a9d31" />
<br/>
<b>Analysis Summary</b>
</td>
</tr>

<tr>
<td align="center">
<img width="250" alt="Picture4" src="https://github.com/user-attachments/assets/02cc880c-35a6-4798-b22a-f7844fa9c728" />
<br/>
<b>AI Chat Interface</b>
</td>

<td align="center">
<img width="250" alt="Picture5" src="https://github.com/user-attachments/assets/dcecf068-0c9d-4d82-b04d-90411fc17727" />
<br/>
<b>Saved Conversations</b>
</td>

<td align="center">
<img src="images/dashboard.png" width="250"/><br/>
<b>Power BI Dashboard</b>
</td>
</tr>
</table>

---

## Future Improvements
- Full automation of data pipelines via APIs  
- Advanced ML models for KPI forecasting  
- Deployment to production environments  

---

## Acknowledgements
Developed in collaboration with Ahamove and RMIT University.

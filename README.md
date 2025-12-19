# ServiceNow_GRC_Project6
AI-Driven Continuous Control Monitoring (ServiceNow GRC)
# EX360-CCM  
## AI-Driven Continuous Control Monitoring (ServiceNow GRC)

EX360-CCM is an enterprise-grade **Continuous Control Monitoring (CCM)** solution built on ServiceNow GRC.  
It demonstrates how AI-assisted logic can continuously evaluate control effectiveness, detect degradation early, and proactively alert stakeholders.

This project focuses on **moving compliance from periodic audits to real-time governance**.

---

## 🎯 Business Problem

Most organizations design strong controls, but lack continuous visibility into whether those controls are:
- Operating effectively
- Gradually degrading
- Failing silently between audits

As a result, control failures are often discovered too late—during audits or incidents.

---

## 💡 Solution Overview

EX360-CCM introduces an **AI-assisted CCM framework** that:

- Separates control design from execution evidence
- Continuously evaluates control execution history
- Calculates AI-based control health scores
- Detects degradation and failures early
- Automatically raises alerts
- Provides executive dashboards for oversight

---

## 🧠 Key Capabilities

### 1. Control Definition & Ownership
- Centralized control catalog
- Clear ownership and accountability
- Defined execution frequency

### 2. Control Execution Tracking
- Execution evidence captured independently
- Pass / Partial / Fail outcomes
- Audit-ready execution history

### 3. AI Control Health Scoring
- Dynamic health score calculation
- Status classification: Healthy / Degrading / Failing
- Explainable AI insights
- Timestamped evaluations

### 4. Proactive Control Alerts
- Automatic alert creation on degradation or failure
- Alert severity based on health status
- Optional notification to control owners

### 5. Executive Visibility
- Real-time CCM dashboard
- Control health distribution
- Active alerts and remediation focus

---

## 🏗️ Architecture Overview

**Core Tables**
- `u_control_definition` – Control design & AI health insights
- `u_control_execution` – Control execution evidence
- `u_control_alert` – AI-generated degradation alerts

**Automation Components**
- Business Rules for AI health scoring
- Flow Designer for alert creation
- Dashboards for executive oversight

---

## 📸 Screenshots

Included screenshots:
- Control health scoring on definition record
- Degrading / failing controls
- Alert records
- CCM executive dashboard

(See `/screenshots` folder)

---

## 🧭 Module Alignment

- **Primary Module:** ServiceNow GRC / IRM  
- **Secondary Domains:** Compliance, Security, IT Risk  

This project reflects real-world CCM patterns used in mature enterprise governance programs.

---

## 🚀 Why This Project Matters

EX360-CCM demonstrates how AI can enhance—not replace—governance by:
- Providing explainable insights
- Enforcing accountability
- Enabling proactive compliance monitoring

This shifts GRC from reactive audits to continuous assurance.

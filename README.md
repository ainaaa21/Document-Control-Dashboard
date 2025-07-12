# 📋 Document Control System (DCS) Dashboard

## 📌 Overview
This dashboard was built to improve the **Document Control System (DCS)** — a platform that stores important documents like SOPs, control plans, and work guidelines used by different departments.

Previously, users had to download Excel files or go through multiple pages just to find a document. This project aimed to make that process faster and easier using **Power BI**.

Using **Power BI**, I imported document data such as Document ID, Title, Type, Function, Owner, Work Area, and Status **directly from the Oracle database**. The result was an **interactive dashboard** that lets users filter, search, and download documents easily from one place.

---

## 🔐 Confidentiality Note
*All data shown has been recreated or anonymized to protect confidentiality. Visuals are used solely to demonstrate the solution's structure and logic.*

---

## 🎯 Problem Statement  
Previously, users had to navigate through multiple pages or download Excel files to search and filter documents in the Document Control System (DCS). This process was time-consuming, inconvenient, and not user-friendly.

The goal of this project was to improve the DCS by creating a **single-page Power BI dashboard** where users could easily **search and filter documents** in real-time. This enhancement simplified document access, reduced manual effort, and made the system more efficient and accessible.

---

## ✅ Solution
The **DCS Dashboard** helped solve these problems by:
- 🔗 **Connecting directly** to the Oracle database for the latest data  
- 📑 Allowing users to **filter and search** documents in real-time  
- 📥 Adding **download links** for easy file access  
- 📊 Showing document stats (e.g., published vs expired)

---

## 🛠 Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI** | Building and designing the dashboard |
| **Oracle DB (Direct Import)** | Bringing in document data |
| **Power Query** | Cleaning and shaping the data |
| **Hyperlink Integration** | Letting users download files easily |

---

## 🧭 Project Walkthrough

### 🔍 Step 1: Dashboard Preview  
This is the main interface that allows users to view, filter, and search documents. Summary tiles show the number of published and expired documents.

<p align="center">
  <img src="sample-screenshots/dashboard-preview.png" alt="Dashboard Preview" width="700"/>
</p>

*Main Power BI dashboard with filters and document status metrics.*

---

### 🧠 Step 2: Table Relationships  
Relationships between tables were created in Power BI to ensure correct filtering and interaction across all document fields like type, department, and expiry status.

<p align="center">
  <img src="sample-screenshots/table-relationship.png" alt="Table Relationship" width="700"/>
</p>

*Data model structure (image recreated and intentionally blurred to protect internal table schema).*

---

### ✅ Step 3: Scenario – Document Search  
This example shows how a user can filter and search documents by fields such as **document type** and **function/department** to quickly find the needed files.

<p align="center">
  <img src="sample-screenshots/dashboard-scenario1.png" alt="Document Search Scenario" width="700"/>
</p>

*Real-time search scenario using filters to narrow down document results.*

---

### 🧾 Step 4: Scenario – Search by Owner Name  
This scenario demonstrates how a user can locate documents by entering part of the **Owner Name**, such as the responsible person or document creator.

<p align="center">
  <img src="sample-screenshots/dashboard-scenario2.png" alt="Document Download Scenario" width="700"/>
</p>

*Example showing how to filter documents by document owner.*

---

## 🔍 Key Features
- 🔎 Filter documents by department, work area, document ID, or owner
- 📥 Clickable hyperlinks for direct file downloads
- 📊 Summary cards for published vs expired documents
- 🔄 Live data refresh via Oracle database connection

---

## 📈 Impact
- ⏱️ Cut search time from minutes to seconds  
- 📉 Removed the need for manual Excel filtering  
- 💡 Improved document access for multiple teams  
- ✅ Positive feedback for ease of use and visual clarity

---

## 🙋‍♀️ About Me
I’m a Computer Science graduate who enjoys solving problems through **data analytics and automation**. I use tools like Power BI, SQL, and Python to turn raw data into useful solutions.

[🔗 LinkedIn](https://www.linkedin.com/in/ainamardhiah2107/)

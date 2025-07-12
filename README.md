# 📋 Document Control System (DCS) Dashboard

## 📌 Overview
During my internship, I created this dashboard to improve the **Document Control System (DCS)** — a platform that stores important documents like SOPs, control plans, and work guidelines used by different departments.

Before this, users had to download Excel files or go through many pages just to find a document. This project aimed to make that process faster and easier using **Power BI**.

Using **Power BI**, I imported document data like Document ID, Title, Type, Function, Owner, Work Area, and Status **directly from the Oracle database**. The result was an **interactive dashboard** that let users filter, search, and download documents easily from one place.

---

## 🔐 Confidentiality Note
*This project was completed during my internship. All data shown has been recreated or anonymized to protect confidentiality. Visuals are only for demonstrating structure and logic.*

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
Users can view and filter all documents by key details. The dashboard also shows totals for published and expired documents.

<p align="center">
  <img src="sample-screenshots/dcs-overview.png" alt="DCS Dashboard Preview" width="700"/>
</p>

*Dashboard showing filters and document stats.*

---

### 🗄️ Step 2: Data Extraction Using SQL
Document details were pulled directly from **Oracle database** tables. Only needed fields were imported to keep things efficient.

<p align="center">
  <img src="sample-screenshots/dcs-sql.png" alt="SQL Snippet" width="700"/>
</p>

*SQL used to get document info from the database.*  
🔗 [View full SQL logic](dcs-query.sql)

---

### 🧠 Step 3: Search & Hyperlink Logic
Once the data was loaded, filters and simple DAX measures were used to count documents. Each row had a link to let users open or download the document.

<p align="center">
  <img src="sample-screenshots/dcs-hyperlink.png" alt="Hyperlink Logic" width="700"/>
</p>

*Power BI table showing document names and clickable links.*

---

### ✅ Step 4: User Experience Scenario
Now, users can just type part of a document title or select a department to quickly find and open the file they need.

<p align="center">
  <img src="sample-screenshots/dcs-filter-demo.png" alt="Filter Scenario" width="700"/>
</p>

*Example showing how easy it is to filter and download documents.*

---

## 🔍 Key Features
- 🔎 Filter documents by department, work area, or ID
- 📥 Click to download any document instantly
- 📊 Track published vs expired files at a glance
- 🔄 Data is kept up to date from the Oracle system

---

## 📈 Impact
- Cut down search time from minutes to seconds
- No need to export or manually filter Excel files
- Easier document access across teams
- Positive user feedback for speed and convenience

---

## 🙋‍♀️ About Me
I’m a Computer Science graduate who enjoys solving problems through **data analytics and automation**. I use tools like Power BI, SQL, and Python to turn raw data into useful solutions.

[🔗 LinkedIn](https://www.linkedin.com/in/ainamardhiah2107/)

# Operational-Risk-Automation-System-
Developed a lightweight system simulating RBC’s front-to-back trade operations. Automated trade matching, EOD settlement checks, and CTM allocation tracking using Python and Google Colab. Designed to reduce manual processing, flag unmatched and late trades, and support operational reporting with real-time KPIs and dynamic visualizations.

# 🏦 Operational Risk Automation System

📊 A Python-based operational risk automation dashboard built using **Google Colab**, simulating trade match data for Royal Bank of Canada (RBC). This dashboard identifies unmatched trades, late confirmations, and CTM allocation issues, and visualizes the insights using interactive charts.

Author: **Danish Aizzat Bin Shaifulnizam**  
Email: **danishaizzat@gmail.com**  
Location: **Cyberjaya, Malaysia**  
Date Created: **July 2025**

---

## 📌 Project Overview

This project automates operational risk analysis for trade matching workflows, simulating RBC’s daily support tasks using mock trade data. It detects late matches, monitors CTM allocations, identifies unmatched confirmations, and flags end-of-day breaches. The system produces visual dashboards and audit logs to support trade validation, risk escalation, and reporting accuracy, closely aligning with real RBC operations.

It processes mock RBC trade data to simulate:

- Match status detection (Matched, Unmatched, Late)
- End-of-day breach detection (after 3PM)
- CTM allocation tracking
- Confirmation status by counterparty
- Visual risk dashboards for decision-makers

---

## Instructions (No Installation Needed)

You can **view and run everything directly in your browser** using Google Colab:

Step 1. Go to the GitHub repo:  
   [🔗 RBC Operational Risk Automation System (GitHub)](https://github.com/danish330/Royal-Bank-of-Canada-Operational-Risk-Automation-System-)

Step 2. Click on:  
   **`Royal_Bank_of_Canada_Operational_Risk_Automation_System.ipynb`**

Step 3. At the top of the notebook preview, click:  
   **“Open in Colab”**

Step 4. In Colab, click the button:  
   **`Click **“Run All”** from the top, just below "tools" -> Run Anyways.

Step 5. Wait a few seconds, then scroll down to see all the results of this system:

   - ✅ Trade Match Status (Pie Chart)
   - 📤 CTM Allocation Status (Pie Chart)
   - 🧑‍💼 Trades by Trader & Match Status (Grouped Bar)
   - 🏦 Counterparty Confirmation Tracker (Histogram)
   - 📋 Full Trade Audit Log (Data Table)
   - 📣 Late Matches After 3 PM (Escalation Report)

All visualizations are fully interactive and automatically generated.

# Clinic Operations & Data Management Systems

This repository contains two operational frameworks designed to improve inventory accuracy and streamline patient communication for a small clinic environment. These systems focus on **practicality**, **protecting doctor time**, and **low-cost implementation** using Google Workspace.

---

## 🛠️ Project Overview

In a typical small clinic, manual data entry and "WhatsApp chaos" often lead to financial loss and clinical burnout. These solutions move away from complex ERP changes and instead focus on **daily micro-habits** that can be managed by a Clinic Analyst in under 30 minutes a day.

### 📁 Repository Structure
* **Daily Pharmacy Inventory Micro-Audit.docx**: A Daily Micro-Audit routine for high-risk pharmacy stock.
* **Patient Care Control & WhatsApp Management.docx**: A centralized control system for patient follow-ups and inquiries.
* **Voice_Note_Explanation.mp3**: A 2-minute audio walkthrough of the system logic.

---

## 💊 Task 1: Daily Pharmacy Inventory Micro-Audit
**Problem:** Medicines are not barcoded, and sales entries are typed manually, leading to frequent inventory "shocks" at month-end.

**Key Features:**
* **High-Risk Watch List:** Focuses only on high-volume or confusingly named medicines (e.g., Dolo 650, Azithromycin).
* **Data Normalization:** A process to map manual typos (like "Dolo kind") back to a Master Name.
* **The 2% Tolerance Rule:** A logic-based approach to investigating variances without over-analyzing minor human errors.

---

## 📱 Task 2: Patient Care Control & WhatsApp Management
**Problem:** The doctor is overwhelmed by ad-hoc WhatsApp queries and manual follow-up reminders.

**Key Features:**
* **Care Control Sheet:** A single Google Sheet "hub" where all messages are drafted and approved.
* **Doctor Review Window:** Reduces doctor input to a single 10-minute session where they dictate answers instead of typing.
* **Boundary Enforcement:** Uses a Google Form flow to move patient inquiries from personal DMs into a structured system.

---

## 🎙️ Audio Explanation
The repository includes a voice recording that explains:
1.  How the systems absorb human error.
2.  The logic behind the High-Risk watch lists.
3.  How these systems ensure the doctor spends **less than 15 minutes** on non-clinical tasks.

---

## ⚙️ Tech Stack
* **Google Sheets:** Central databases and audit logs.
* **Google Docs:** Formatting the plan and orgamizing the checklist.
* **Google Forms:** Structured patient inquiry intake.
* **HMS Data:** Raw source for appointments and prescriptions.
* **Markdown:** Documentation and SOP formatting.

---

**Developed by:** Jasmitha Kancharlapalli
**Objective:** Operational Efficiency & Business Analysis for Healthcare.

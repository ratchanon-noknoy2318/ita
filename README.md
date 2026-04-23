# Kosamphi ITA 2024 🏥🏛️

A production-ready legacy PHP system designed to manage the **Integrity and Transparency Assessment (ITA)** workflows for government healthcare institutions under the **Ministry of Public Health (MOPH)**, Thailand.

## 🚀 Impact & Performance
- **Critical Bug Resolution**: Identified and resolved widespread **HTTP 404 errors** across **MOIT 1–22 modules** within a 24-hour window using advanced server log analysis.
- **Compliance Enabled**: Successfully supports live ITA evaluations, ensuring the institution meets national transparency standards set by the NACC.
- **Production Proven**: Actively used within the MOPH government infrastructure to manage reporting and compliance data.

## 📋 Overview
The system automates the submission and tracking of **MOIT (MOPH Open Data Integrity and Transparency Assessment)** indicators. It allows healthcare units to disclose public information, manage internal integrity assessments (IIT), and handle external stakeholder feedback (EIT) as required by the 2024 [MOPH ITA Manual](https://stopcorruption.moph.go.th/application/editors/userfiles/files/%E0%B8%84%E0%B8%B9%E0%B9%88%E0%B8%A1%E0%B8%B7%E0%B8%AD%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%9B%E0%B8%A3%E0%B8%B0%E0%B9%80%E0%B8%A1%E0%B8%B4%E0%B8%99%20MOPH%20ITA%20%E0%B8%9B%E0%B8%B5%E0%B8%87%E0%B8%9A%E0%B8%AF%202567.pdf).

## 🛠️ Tech Stack
- **Language**: PHP (Legacy Monolith)
- **Database**: MySQL
- **Frontend**: HTML5, CSS3, JavaScript
- **Infrastructure**: MOPH Government Hosting Environment

## 🏗️ Architecture
The system follows a classic monolithic pattern optimized for low-latency delivery over government intranets:
`User` ↔️ `PHP Engine` ↔️ `MySQL Data Store` ↔️ `MOPH Private Cloud`

## 📂 Key Modules (MOIT 1-22)
- **MOIT 1-2**: Information Disclosure & Current News
- **MOIT 3-4**: Procurement & Budgeting Transparency
- **MOIT 5-8**: HR Management & Resource Usage
- **MOIT 21-22**: Human Rights & Anti-Harassment Reporting

## 🛡️ Security & Governance
- **Access Control**: Role-based access for auditors and healthcare staff.
- **Data Integrity**: Optimized for the **MITAS** (MOPH Integrity and Transparency Assessment System) integration requirements.

## 📄 License
This project is developed for government healthcare compliance.

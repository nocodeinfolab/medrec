# MedRec – In-Patient Medical Record System

**MedRec** is a browser-based hospital information tool for managing in-patient admissions. It integrates directly with **Baserow APIs** to give doctors and staff a clean interface for recording and reviewing patient data.

---

## ✨ Features

- **Patient Profile**
  - Upload or capture a patient photo
  - Store and display demographics and admission info

- **Admission Records**
  - View reason for admission, ward/bed details, and referring doctor

- **Current Medications**
  - Auto-fetch meds administered in the last 24 hours
  - Interactive “See More / See Less” toggle

- **Vital Signs**
  - Record and view vitals (Temp, Pulse, BP, Respiration, SPO2, Weight, Height, BMI)
  - Trend charts for **Temperature** and **Blood Pressure**
  - Expandable cards + popup forms for adding new vitals

- **Initial Observation & Diagnosis**
  - Capture complaints, history, exam findings, diagnosis, and plan
  - Update existing observations

- **Discharge Workflow**
  - Confirm discharge date and status (Recovered, Referred, Deceased, etc.)
  - Add discharge summary and close admission

---

## 🛠 Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Charts**: Chart.js  
- **Backend**: [Baserow](https://baserow.io) API (Admissions, Vitals, Medications, Initial Obs, Discharges)  
- **Icons**: Font Awesome  
- **Storage**: LocalStorage (for demo photo saving)  

---

## 🚀 Usage

1. Update the **API Token** and **Table IDs** in the `CONFIG` section of `index.html`.  
2. Open `index.html` in a modern browser.  
3. System will auto-fetch patient data for the configured Admission ID.  

---

## 👤 Author

Built by **[nocodeinfolab](https://github.com/nocodeinfolab)**  
Helping healthcare providers, law firms, and startups turn data into working apps — fast and clean.


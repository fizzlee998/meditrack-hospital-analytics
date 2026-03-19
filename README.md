# MediTrack Nigeria — Hospital Analytics Case Study

## Overview

A complete end-to-end hospital analytics project for a fictional Nigerian
multi-department hospital called MediTrack, analysing 25,000 patients,
62,135 appointments, and 43,893 billing records across July 2023 to June 2024.

This project demonstrates healthcare data analytics — from patient dropout
analysis and no-show patterns to HMO reimbursement impact and department
performance benchmarking.

---

## Business Problems Solved

| Problem | Description |
|---|---|
| Revenue Fluctuation | Why is revenue declining despite growing patient numbers? |
| No-Show Crisis | Which departments have the worst no-show rates and why? |
| Patient Dropout | Which patients are most at risk of dropping out of care? |
| Channel Quality | Which registration channel brings the most loyal patients? |
| Wait Times and Satisfaction | How do we improve patient experience and reduce wait times? |

---

## Key Findings

- HMO reimbursement cut from 72% to 55% in January 2024 created a ₦28.6M+ revenue shortfall
- Mental Health (44.7%) and Dental (43.4%) have critically high no-show rates
- Maternity wait times doubled from 37.7 to 84.3 minutes after a staff shortage — satisfaction crashed from 4.1 to 2.7 out of 5
- Doctor Referral patients have a 32.3% active rate — 47% better than Walk-in patients
- 73.4% of patients have dropped out of care — Out-of-Pocket payers churn fastest due to price sensitivity

---

## Project Files

| File | Description |
|---|---|
| `MediTrack_Analysis.ipynb` | Full Python analysis in Jupyter notebook |
| `MediTrack_Dashboard.html` | Interactive dashboard — download and open in any browser |
| `meditrack_patients.csv` | 25,000 synthetic patient records |
| `meditrack_appointments.csv` | 62,135 appointment records across 10 departments |
| `meditrack_billing.csv` | 43,893 billing records with HMO and out-of-pocket breakdown |

---

## How to View the Dashboard

1. Download `MediTrack_Dashboard.html`
2. Open it in any browser — Chrome, Firefox, or Edge
3. No installation or internet connection needed

---

## How to Run the Analysis
```bash
pip install pandas numpy matplotlib jupyter

jupyter notebook
```

Open `MediTrack_Analysis.ipynb` and run all cells from top to bottom.

---

## Tools Used

| Tool | Purpose |
|---|---|
| Python with pandas | Data generation, cleaning, and analysis |
| matplotlib | Data visualisation and chart generation |
| Jupyter Notebook | Analysis environment |
| Chart.js | Interactive dashboard visualisations |
| GitHub | Version control and portfolio hosting |

---

## Dataset Note

This is a synthetic dataset generated with realistic Nigerian healthcare
patterns — including HMO reimbursement cuts, department-specific no-show
rates, staff shortage effects on wait times, and channel-based patient
retention differences. All names, IDs, and figures are fictional.

---

## Skills Demonstrated

Patient dropout analysis, no-show rate analysis, revenue trend analysis,
HMO reimbursement modelling, wait time vs satisfaction correlation,
channel quality scoring, healthcare KPIs, Python, matplotlib, Jupyter.

# Game Log Analytics Dashboard
<img width="1863" height="1077" alt="image" src="https://github.com/user-attachments/assets/a739fdec-f9ef-4984-923c-4e6afb3932e2" />


## Project Overview

This project analyzes player behavior, retention, monetization, and gameplay progression using a simulated mobile game event dataset.

The dashboard was built using SQL, BigQuery, and Power BI to simulate a real-world game analytics workflow commonly used in mobile game studios.

---

## Tech Stack

- SQL (BigQuery)
- Power BI
- DAX
- Python (Pandas)

---

## Dataset

The dataset contains simulated game events such as:
- Install
- Session Start
- Level Start
- Level Complete
- Purchase

Main tables:
- game_events
- users
- retention_summary
- user_summary

---

## Dashboard Features

### Executive KPIs
- DAU
- Revenue
- Payers
- ARPU / ARPPU
- Install Tracking

### Retention Analysis
- D1 Retention
- D7 Retention
- Weekly Cohort Retention

### Funnel Analysis
- Install → Session → Level Start → Level Complete → Purchase

### Level Analytics
- Level Completion Rate
- Player Drop-off Analysis

---

## Business Questions

- How well does the game retain users over time?
- Which levels have the highest drop-off rates?
- What percentage of users become paying users?
- How does player engagement impact revenue?

---

## Key Insights

- Retention decreases significantly after the first few days.
- Higher levels show lower completion rates, indicating increased difficulty.
- Revenue trends generally follow DAU fluctuations.
- Funnel analysis helps identify player drop-off points during gameplay progression.

---

## Project Structure

```text
project/
│
├── data/
├── sql/
├── dashboards/
├── images/
└── README.md
```

---

## Conclusion

This project demonstrates:
- SQL-based analytics workflows
- Cohort retention analysis
- Funnel analysis
- KPI monitoring
- Power BI dashboard development
- Basic game analytics concepts

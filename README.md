# HEALTHCONNECT-FINAL-PROJECT
 HealthConnect Clinic — Data Analytics Track
AnalystLab Africa Experience Lab | HealthConnect Clinic Experience Lab

Reducing missed appointments and improving patient support at a fictional healthcare clinic, using exploratory data analysis, KPI development, statistical validation, and an interactive Power BI dashboard.

Project question: How can HealthConnect Clinic use data and AI to reduce missed appointments and improve the patient support experience?


📊 Dashboard Overview

Page 1 — Executive Overview
Headline KPIs (Total Appointments, Attended, Cancelled, No-Shows, Overall No-Show Rate, Repeat No-Show Rate) alongside the primary drivers: distance band, reminder status, booking lead time, and prior no-show history — each with a reminder-status breakdown for interaction context.

Page 2 — Secondary Drivers
Day of week, time of day, reminder channel, appointment type, and the original 3-factor risk segmentation (Low/Medium/High Risk), with synced slicers carried over from Page 1.

Page 3 — Validation (Week 6, tested & refined in Week 7)
A validation table confirming which Week 5 factors are statistically significant, the refined 4-factor risk segment (Critical/Medium/Minimal Risk), a live Critical Risk Count — now labelled "Critical Risk Count (94 eligible for no-show rate)" following Week 7 testing — and a lead-time-by-distance interaction chart.

 Key Findings

Finding | Result 
Overall no-show rate -51.2% (n = 4,737 eligible appointments) 
Strongest validated driver -Booking lead time=29.5% (0–7 days), 71.4% (45+ days) 
Repeat no-show rate-57.8% (has prior no-show) vs. 46.3% (clean record) 
Distance effect- 48.7% (<5km), 56.9% (>15km) |
Reminder effect - 54.6% (no reminder), 49.9% (reminder sent); SMS performs best
Refined risk segment (Week 6)- Critical Risk: 80.9% vs. Minimal Risk: 22.4%- a validated 58.5-point spread 

Testing & Refinement (Week 7)

Every headline KPI card was independently recomputed against the cleaned dataset, and the dashboard itself was stress-tested rather than assumed correct.


Limitations

Dataset is fictional/simulated and does not reflect real-world clinical behaviour
Cancelled appointments are excluded from the no-show rate denominator (pending formal business confirmation)
Critical/Minimal risk segments are based on ~100 appointments each; directionally reliable but should be re-validated as more data becomes available

Final Outcome (Week 8)

The Data Analytics contribution is complete: statistically validated (Week 6), functionally tested with real defects found and fixed (Week 7), and translated into a plain-language final report and presentation deck for non-technical stakeholders (Week 8). Cross-checked with the Data Science track to confirm both workstreams describe the same validated risk factors and patient counts.

 Tools Used

Power BI for the interactive dashboard · Microsoft Word for reporting, Claude AI



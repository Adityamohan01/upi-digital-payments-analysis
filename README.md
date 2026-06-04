# UPI & Digital Payments Analysis — India 2022–2025

I built this project because I was curious about how UPI grew so fast in India. Everyone around me — from grocery shops to auto rickshaws — started accepting UPI payments, and I wanted to actually see the numbers behind that change.

So I went directly to NPCI's official website, downloaded the raw data month by month, and analysed it myself.

---

## What I Found

The thing that surprised me most was not the growth in volume — it was the average ticket size dropping from ₹181 in 2022 to ₹135 by 2025. People are not just using UPI for big transfers anymore. They are using it for small everyday payments — chai, auto rides, vegetables. Cash is slowly becoming irrelevant for daily life.

Three findings that stood out:

- UPI transaction volume grew 132% between 2022 and 2024. That is not a trend, that is a shift.
- Average ticket size has been falling every year. More people, smaller amounts, more frequency.
- October to December always spikes — Diwali, Dhanteras, and year-end shopping drive the highest UPI usage every single year without fail.

---

## Dashboard

🔗 [View Live Dashboard on Tableau Public]((https://public.tableau.com/views/UPIDigitalPaymentsAnalysisIndia2022-2025/UPIIndiaDashboard?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link))

---

## Tools I Used

| Tool | Purpose |
|---|---|
| NPCI Official Website | Downloaded raw monthly data directly |
| Google Sheets | Cleaned and structured the data |
| MySQL | Stored data and ran analysis queries |
| Tableau Public | Built the interactive dashboard |

---

## Files in This Repo

| File | What it is |
|---|---|
| upi_master.csv | UPI monthly stats — volume, value, avg ticket size |
| payment_comparison.csv | UPI vs NEFT vs IMPS vs Cards (2022–2025) |
| insert_data.sql | Creates the database and loads all data |
| analysis_queries.sql | 5 queries I wrote to find the insights above |

---

## Data Source

I did not use Kaggle for this. All data was downloaded directly from:

**NPCI Product Statistics** → npci.org.in/what-we-do/upi/product-statistics

Coverage: January 2022 to March 2025 — 39 months of data across 4 payment modes.

---

## About Me

I am Aditya Mohan, a student learning data analytics. This is one of my first end-to-end projects where I collected, cleaned, queried and visualised real data from scratch.

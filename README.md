# 📦 Instant Delivery Delay Analysis (India)

## 📌 Project Overview
Instant delivery platforms in Indian cities promise deliveries within **10–20 minutes**, but customers frequently experience delays.  
This project analyzes **delivery delays**, identifies **root causes**, and recommends **data-driven business actions** to improve on-time delivery.

The project follows a **real-world analytics workflow** used in companies.

---

## 🎯 Problem Statement
Customers using instant delivery e-commerce platforms often receive orders later than promised.  
The objective of this project is to:
- Identify delay patterns
- Understand why delays occur
- Recommend practical business solutions
- Define a monitoring plan to track improvements

---

## 🧠 Project Workflow
### EDA → RCA → Decision → Monitoring


- **EDA (Exploratory Data Analysis):** What is happening?
- **RCA (Root Cause Analysis):** Why is it happening?
- **Decision:** What should be done?
- **Monitoring:** How do we measure success?

---

## 📊 Dataset Description
The dataset is **synthetic but realistic**, simulating real delivery operations.

| Column Name | Description |
|-----------|-------------|
| order_id | Unique order identifier |
| order_date | Order timestamp |
| order_hour | Hour of the day |
| city | Delivery city |
| promised_minutes | Promised delivery time |
| actual_delivery_minutes | Actual delivery time |
| delay_minutes | Actual − Promised |
| traffic_level | Low / Medium / High |
| weather | Clear / Rain |
| rider_available | Yes / No |
| peak_hour | True / False |

---

## 📈 Key KPIs
| KPI | Description |
|---|---|
| Avg Delivery Time | Overall delivery speed |
| Delay Rate | % of delayed orders |
| Avg Delay | Average delay experienced |
| On-Time % | SLA compliance |

---

## 🔍 EDA Summary (What is Happening)
- Around **90% of orders are delayed**
- On-time delivery is approximately **10%**
- Delays are significantly higher during:
  - Peak hours
  - High traffic
  - Rainy weather
  - Rider unavailability
- Peak hours and high traffic show **near 100% delay rate**

---

## 🧠 RCA Summary (Why It Is Happening)
Based on EDA comparisons:
- Rider unavailability leads to guaranteed delays
- Peak-hour demand exceeds delivery capacity
- Traffic congestion makes static delivery promises unrealistic
- Rain amplifies existing delays

### Primary Root Cause
> **Mismatch between rider availability and order demand, especially during peak hours**

---

## ✅ Business Decision
> **Increase rider availability during peak hours using demand forecasting and rider incentives to reduce delivery delays.**

This decision targets the **most impactful and controllable factor** identified through RCA.

---

## 📊 Monitoring Plan
After implementing the decision, performance will be tracked using:

| KPI | Frequency | Expected Outcome |
|---|---|---|
| On-Time % | Daily / Weekly | Increase |
| Delay Rate | Daily / Weekly | Decrease |
| Avg Delay | Weekly | Decrease |
| Peak-Hour Avg Delay | Daily | Reduce significantly |

---

## 🏁 Conclusion
This project demonstrates how data analytics can be applied to:
- Identify operational problems
- Understand root causes
- Recommend actionable business decisions
- Track improvements using KPIs

The **EDA → RCA → Decision → Monitoring** framework makes the analysis business-ready and interview-ready.

---

## 👤 Author
**Manu**  
Aspiring Data Analyst

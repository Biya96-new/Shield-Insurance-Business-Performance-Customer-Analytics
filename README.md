# Shield Insurance – Business Performance & Customer Analytics

## 📌 Project Overview

Shield Insurance is a Power BI analytics project focused on understanding **business performance, customer behaviour, sales modes, and policy preferences** across cities and age groups.

The project transforms raw insurance data into practical business insights to support **customer targeting, sales planning, channel strategy, and risk monitoring**.

---

## 🎯 Business Questions

The analysis focuses on:

- How is the business performing over time?
- Which customer segments and cities contribute most to revenue?
- Which sales modes are preferred by customers?
- When are customers most active?
- How does sales mode preference vary across age groups?
- How do policy choices and settlement patterns vary by age?

---

## 📂 Dataset

The dataset contains information related to:

- Customer demographics
- Policies and coverage
- Premium transactions
- Sales modes
- Dates
- Settlement percentages

**Cities:** Chennai, Delhi, Hyderabad, Indore, Mumbai

**Sales Modes:** Offline-Agent, Offline-Direct, Online-App, Online-Website

---

## 🔄 Data Preparation & Modelling

The raw insurance data was cleaned, structured, and prepared in Power BI before building the dashboard.

### Data Preparation

Key transformations included:

- Created meaningful **age groups** from customer age.
- Added **Day Number** and **Month Number** to the date table.
- Created a **Month-Year** field and applied chronological sorting for accurate monthly analysis.
- Cleaned and structured customer, policy, premium, sales mode, and date information.
- Prepared the data for analysis across **cities, age groups, sales modes, and time periods**.

### Data Modelling & Measures

A relational data model was created between the customer, policy, premium, and date tables.

DAX measures were developed for key business metrics, including:

- Total Revenue
- Total Customers
- Total Coverage
- Total Premium
- Daily Revenue
- Daily Customers
- Policy Growth
- Revenue per Customer
- Customers MoM%
- Revenue MoM%
- Customer and Revenue Contribution

---

## 📊 Business Snapshot

| Metric | Value |
|---|---:|
| Total Revenue | **₹989.25M** |
| Total Customers | **26.84K** |
| Daily Revenue | **₹5.47M** |
| Daily Customers | **148** |


---

# 📈 Dashboard Analysis

## 1. Business Performance

<img width="638" height="396" alt="image" src="https://github.com/user-attachments/assets/de1c39f1-d160-40c9-8d03-ef0ad3108aa6" />

- How is overall revenue and customer performance changing?
- How are policies growing month over month?
- Which customer age groups contribute most?
- Which cities contribute most to the business?
- How does revenue growth compare with customer growth?

### Key Insights

- Shield generated **₹989.25M in revenue from 26.84K customers**.
- Monthly customers remained around **4K from November to February**, before increasing to approximately **7.1K in March**.
- March recorded **+82.27% policy growth**, followed by a **-41.41% decline in April**, indicating a strong but temporary year-end surge.
- Revenue per customer stabilised around **₹36K–₹37K from January onward**, suggesting that revenue growth was driven more by customer volume than by a major increase in revenue per customer.
- Customers aged **31–50 form the core customer base**, while Delhi contributes the highest revenue, supported by its larger customer volume.

---

## 2. Sales Mode Analysis

<img width="637" height="396" alt="image" src="https://github.com/user-attachments/assets/2588a236-cdbb-4c04-af8a-50afa00324f0" />

- Which sales modes contribute most to revenue and customers?
- How does sales mode preference vary across cities?
- When are customers most active?
- Is customer behaviour different between weekdays and weekends?

### Key Insights

- Offline sales account for **71.13% of customers**, compared with **28.87% online**.
- **Offline-Agent contributes 55.67% of revenue**, making it the dominant sales mode.
- Customer and revenue shares across sales modes are closely aligned, indicating that differences are largely driven by customer volume.
- Offline-Agent remains the leading sales mode across cities.
- Weekend customer activity is **more than 2.5× higher than typical weekday activity**, suggesting that customers have more time for financial discussions and policy purchases during weekends.

---

## 3. Age Group Analysis

<img width="638" height="398" alt="image" src="https://github.com/user-attachments/assets/efbddb6a-8115-4068-8953-d6f816deb31d" />

- How does settlement percentage vary across age groups?
- Which sales modes are preferred by different age groups?
- How does policy adoption change across life stages?
- Do older and younger customers show different coverage and premium patterns?

### Key Insights

- Settlement percentage increases from **39.46% among ages 18–24 to 71.68% among ages 65+**.
- Older customer segments tend to have higher coverage values, resulting in greater settlement exposure.
- Policy values vary significantly across age groups, from examples such as **₹2L coverage / ₹5K premium** among younger customers to **₹1Cr / ₹1.2L** for a higher-value older customer policy.
- **Offline-Agent is the preferred sales mode across all age groups**.
- The **31–40 age group is the largest segment**, with approximately **9.9K customers**.
- Policy preferences vary with life stage, with younger customers generally choosing lower coverage while customers with greater financial responsibilities may require higher protection.

---

# 💡 Business Insights

### Customer Growth
Revenue growth is strongly linked to customer volume. With revenue per customer stabilising around **₹36K–₹37K**, increasing the customer base remains an important growth driver.

### March Surge
March recorded **+82.27% policy growth**, followed by a **-41.41% decline in April**, indicating a strong year-end demand spike followed by normalization.

### Sales Mode Preference
**Offline-Agent contributes 55.67% of revenue** and remains the leading sales mode across cities and age groups, highlighting the continued importance of personal guidance in insurance purchases.

### Digital Opportunity
Online channels account for **28.87% of customers**, indicating an opportunity to make digital policy comparison and purchasing more convenient.

### Age-Based Behaviour
The **31–50 age groups form the core customer base**, while older customers tend to have higher-value policies and greater settlement exposure.

### Customer Activity
Weekend activity is **more than 2.5× higher than typical weekday activity**, highlighting an opportunity to align customer engagement with periods of higher activity.

---

# 🚀 Business Actions

Based on the analysis:

- **Strengthen agent-led engagement** while continuing to improve the digital buying experience.
- **Use age and life-stage segmentation** to provide more relevant policy options and communication.
- **Focus customer engagement around weekends**, when activity is significantly higher.
- **Prepare sales capacity and campaigns for March demand** and the subsequent April normalization.
- **Identify high-potential cities and customer segments** for targeted acquisition and retention.
- **Monitor higher-coverage policies** because of their greater settlement exposure.

---

## 🛠️ Tools & Technologies

**Power BI | DAX | Power Query | Data Modelling**

---

## 🔗 Project Links

### 📊 Live Dashboard

> **Power BI Dashboard:** <iframe title="shield_insurance" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiMTAxZWVkZDktNzQzYS00MjFiLThjYTYtMjg2ZjE5NzZjNjc5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9" frameborder="0" allowFullScreen="true"></iframe>

<iframe title="shield_insurance" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiMGM5MGM5ZjktOGJhMy00NDg4LWE5ZjktYWJmNTkyZWM5YjczIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9" frameborder="0" allowFullScreen="true"></iframe>

### 🎥 Video Presentation

> **Project Walkthrough:** [Watch Presentation](YOUR_VIDEO_LINK)

### 📑 Project Presentation

> **View Project Presentation:** [Open PPT](YOUR_PPT_LINK)

---

## 👤 Connect With Me

**Biya Rocky**  
Data Analyst | Power BI | SQL | Data Visualization

[LinkedIn][(YOUR_LINKEDIN_LINK)](https://www.linkedin.com/in/biya-rocky-dataanalyst/) 
---


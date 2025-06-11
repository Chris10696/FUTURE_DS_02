# 📊 Social Media Campaign Performance Dashboard

**Future Interns – Data Science & Analytics Internship (Task 2)**

This repository contains my solution for Task 2 of the **Future Interns Data Science & Analytics Program**, where I analyzed digital ad campaign data from Facebook and Instagram to evaluate performance metrics and generate business insights.

The project delivers a multi-page **Power BI dashboard** that tracks engagement, cost-effectiveness, and campaign ROI across time and demographics. This dashboard is designed to support marketing teams in optimizing targeting, ad spend, and conversion strategies.

---

## 🧰 Tools & Technologies Used

| Tool        | Purpose                                         |
| ----------- | ----------------------------------------------- |
| Power BI    | Dashboard creation, DAX measures, visual design |
| Power Query | Data cleaning and transformation                |
| DAX         | KPI measures like CTR, CPC, ROI                 |
| Excel       | Initial exploration of raw campaign data        |

---

## 📁 Files Included

| File Name                                         | Description                                 |
| ------------------------------------------------- | ------------------------------------------- |
| `task2.pbix`                                      | Power BI file with dashboard and DAX logic  |
| `data.csv`                                        | Raw social media ad campaign dataset        |
| `Social Media Campaign Performance Dashboard.pdf` | Exported overview of the finished dashboard |

---

## 📊 Dashboard Structure

The dashboard is structured into multiple pages for clarity and storytelling:

### 1. 🏠 Overview Page

* High-level KPIs: CTR, CPC, ROI, Clicks, Impressions, Spend, Conversion Rate
* Slicers for Year, Gender, and Age
* Charts for engagement over time and by age

### 2. 👥 Demographics Page

* CPC and ROI by Gender
* CTR and Clicks by Age Group
* Conversion breakdown by segment

### 3. 📆 Time Trends Page

* Line charts to monitor CTR, ROI, and Conversion Rate over time
* Date and month-based slicers

### 4. 📂 Campaign View Page

* Campaign-level table showing clicks, conversions, spend, and ROI
* Visual comparisons of ROI and budget per campaign

---

## 📐 Key DAX Measures

* **CTR (Click-Through Rate)** = `Clicks / Impressions`
* **CPC (Cost Per Click)** = `Spend / Clicks`
* **Conversion Rate** = `Approved Conversions / Clicks`
* **ROI (Return on Investment)** =

  $$
  \frac{(\text{Approved Conversions} \times \text{Conversion Value}) - \text{Spend}}{\text{Spend}}
  $$

  A **user-defined parameter** allows the marketer to adjust the value per conversion (e.g., \$10–\$100), dynamically updating ROI in real time.

---

## 🔍 Key Insights & Observations

* CTR and Conversion Rate vary significantly by age and gender
* Some campaigns yield high engagement but low ROI — showing room for landing page or offer optimization
* Seasonal trends affect ad performance, reinforcing the importance of time-based targeting
* A flexible ROI parameter allows the dashboard to adapt to different business models or goals

---

## 🎯 Skills Demonstrated

* Building dynamic, multi-page dashboards
* Applying DAX for business KPIs and metrics
* Modeling relationships between date and ad data
* Designing user-friendly visual narratives using slicers, cards, and charts
* Using page navigation buttons to create an intuitive app-like experience

---

## 🙌 Acknowledgment

This project was completed as part of the **#FutureInterns** program to build real-world data analytics skills using modern tools like Power BI, Excel, and DAX.

---

## 🏷️ Tags

\#PowerBI #MarketingAnalytics #SocialMediaData #CTR #ROI #DAX #DataVisualization #FutureInterns #CampaignPerformance

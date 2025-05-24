# Digital Campaign efficiency
## 📊 Evaluating the Effectiveness of Digital Marketing Campaigns for a Pharma Product Launch

This project simulates and analyzes digital marketing campaign data for a fictional pharmaceutical product launch. It focuses on channel effectiveness, campaign performance by stage and ad type, device-level engagement, and profitability over time.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Objective](#objective)
- [Data Simulation](#data-simulation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Profitability & ROI Analysis](#profitability--roi-analysis)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Tools Used](#tools-used)
- [How to Run](#how-to-run)
- [Project Structure](#project-structure)
- [License](#license)

---

## 🧩 Overview

This project emulates a real-world pharma marketing scenario. The synthetic dataset includes marketing channel interactions, ad campaign types, device performance, and anomalies like ad fatigue and end-of-month spikes/dips to reflect realistic challenges faced by marketing analysts.

---

## 🎯 Objective

- Analyze digital campaign effectiveness by Channel, Campaign Stage, Ad Type, and Device.
- Uncover insights around Return on Ad Spend (ROAS) and campaign profitability.
- Identify underperforming segments and make optimization recommendations.
- Simulate anomalies such as revenue dips, null values, and campaign shutdown behavior.

---

## 🛠️ Data Simulation

The dataset was generated using Python, simulating:
- **Date range:** 3 months daily
- **Channels:** Google, Facebook, Email, etc.
- **Campaigns:** Awareness, Consideration, Conversion
- **Ad Types:** Text, Display, Video
- **Devices:** Desktop, Mobile, Tablet

Simulated features:
- Seasonal trends and holiday effects
- Campaign fatigue and termination logic
- Missing and diminishing revenue to mimic real-world behavior
- Realistic weights for channel and device occurrences

---

## 📈 Exploratory Data Analysis (EDA)

- Weekly trends in spend, revenue, clicks, and conversions
- Channel and device performance comparisons
- Ad Type breakdown within each campaign stage
- Anomaly detection via missing values and declining ROAS

---

## 💰 Profitability & ROI Analysis

- **ROAS (Return on Ad Spend)** = Revenue / Spend  
- **Profit** = Revenue - Spend  
- Weekly and channel-wise ROAS tracking
- ROAS outliers, negative ROI events, and campaign shutdown patterns

---

## 📊 Key Findings

- Google and Facebook had the highest spend and revenue contribution.
- Mobile led in engagement but desktop showed better conversion rates.
- Conversion campaigns with video ads yielded the highest ROAS.
- Simulated campaign fatigue led to revenue dips and budget shutdowns.

---

## 💡 Recommendations

- Invest more in high-performing combinations (e.g., Facebook + Mobile + Video).
- Terminate underperforming campaigns promptly based on ROI thresholds.
- Rotate ad creatives frequently to combat fatigue.
- Adjust spend dynamically based on seasonal trends and anomaly alerts.

---

## 🧰 Tools Used

- **Python**: Data simulation and analysis  
- **Pandas / NumPy**: Data wrangling  
- **Matplotlib / Seaborn**: Data visualization  
- **Jupyter Notebook**: Analysis & documentation

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pharma-marketing-campaign-analysis.git
   cd pharma-marketing-campaign-analysis

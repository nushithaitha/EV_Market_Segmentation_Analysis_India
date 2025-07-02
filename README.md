# 📘EV Market & Customer Segmentation Analysis

## 🔍 Project Overview

This document outlines the key research questions, customer segmentation strategy, and decision-support framework for an electric vehicle (EV) startup in India. The goal is to determine **what type of EV to manufacture**, **whom to target**, **where to launch**, and **how to price and position** the vehicle—based on data-driven insights from market analysis and customer research.

---

## 📁 Project Structure

```
EV-Market-Research/
├── 📊 dataset/
│   ├── codebook.docx                        # Documentation of EV sales dataset
|   ├── ev_sales.xlsx                        #dataset for vehicle Analysis
|   ├── EV_Sales_Cleaned_Upto_2025.csv
│   ├── Questionnaire.docx                   # Survey forms and questionnaires
│   ├── Response.xlsx 
│   └── SPSS.sav
|
|── Project Reoprt                           # Detailed report of the project
|
├── 🖼️ images/
|
├── 📓 notebooks/
│   ├── 01_Vehicle_Segmentation.ipynb       # Market size, trends, and vehicle type analysis
│   ├── 02_Customer_Segmentation.ipynb      # Customer profiling and targeting strategy
|            
├──  README.md
|
└── 📋 requirements.txt                     # Python dependencies
```

---

## 🧩 Key Research Questions

### 🚙 Market Understanding

* **What type of EV should be produced?**
  → Analyze demand across 2-wheelers (2W), 3-wheelers (3W), 4-wheelers (4W), and cargo vehicles.

* **Who are the potential customers?**
  → Identify key use-cases: personal, commercial, delivery, ride-sharing, fleet, etc.

* **Which Indian cities/regions are best suited for early EV adoption?**
  → Evaluate infrastructure, government policies, and user readiness.

* **What is the size of the current and future EV user base in India?**
  → Estimate market size, growth rate, and segment-wise penetration.

* **What vehicle types are trending?**
  → Compare internal combustion engine (ICE) vs EV trends across categories.

### 👤 Customer Segmentation

* **Who are the early adopters of EVs in India?**
  → Segment customers by age, income, profession, lifestyle, and location.

* **Which segments should be prioritized?**
  → Focus on groups with high intent, large size, and specific unmet needs.

### 📍 Location Selection

* **Which cities have strong EV charging infrastructure?**
  → Shortlist cities with public and private charging stations.

* **What is the EV adoption lifecycle across cities?**
  → Categorize cities into Innovators → Early Adopters → Early Majority.

### 💸 Product & Pricing Strategy

* **What pricing range is viable for early EV adopters?**
  → Study income brackets, loan availability, and willingness to pay.

* **How are competitors pricing their EVs?**
  → Benchmark against competitors and assess buyer affordability.

* **What motivates EV buyers?**
  → Understand if purchase is driven by savings, eco-consciousness, tech appeal, or status.

---

## 🎯 Decision Support Framework

| Decision Point               | Research Input Needed                                             |
| ---------------------------- | ----------------------------------------------------------------- |
| 🚗 What type of EV to build? | Analyze market size and sales by vehicle segment (2W/3W/4W/Cargo) |
| 👥 Who to sell it to?        | Segment target customers: personal, commercial, delivery, etc.    |
| 📍 Where to launch first?    | Focus on cities with infrastructure and high readiness            |
| 💰 How to price it?          | Use competitor pricing, income data, and subsidy analysis         |
| 📈 Why will people buy it?   | Identify key buyer motivations and pain points                    |

---

## 🚀 Getting Started

### 🔧 Prerequisites

Ensure you have the following installed:

```bash
pip install -r requirements.txt
```

* Python 3.8+
* Jupyter Notebook
* Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `scikit-learn`

---

## 🧪 Running the Analysis

* **Market Analysis:**
  Open `notebooks/01_Vehicle_Segmentation.ipynb` to explore EV market trends, segment share, and growth.

* **Customer Segmentation:**
  Open `notebooks/02_Customer_Segmentation.ipynb` to understand key personas and customer intent.

---

## 📈 Key Insights & Recommendations

### 🧭 Market Opportunity

* **2-wheelers** dominate in current EV sales, showing high acceptance among individual buyers.
* **3-wheelers (cargo/passenger)** exhibit the highest commercial growth potential.
* **Tier-1 cities** are mature markets; **Tier-2 cities** present the next major opportunity wave.

### 🎯 Target Customers

* **Primary Segments:**

  * Urban delivery executives
  * Fleet operators and ride-hailing services
  * Tech-savvy millennial commuters

* **Secondary Segments:**

  * Eco-conscious professionals
  * Budget-conscious daily commuters

🙋 Author
Nushith Aitha
📍 India
📧 aithanushith@gmail.com

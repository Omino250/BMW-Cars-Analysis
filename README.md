# 🚗📊 BMW Cars Market Analysis & Performance
## 🎯 Project Overview

The BMW automotive market spans a wide range of models, fuel technologies, and customer preferences. However, raw listing data alone does not clearly explain which models drive volume, how market demand has evolved, or where BMW’s value and tax exposure truly lie.

This project analyzes BMW car listings data sourced from Kaggle, transforming raw vehicle records into a clear analytical story using Power Query for data preparation and Power BI for visualization.

The dashboard answers critical business questions such as:

• Which BMW models dominate the market by volume and value

• How BMW listings have changed over time

• What fuel types and transmissions customers actually prefer

• How tax and pricing are distributed across models

• What these patterns reveal about BMW’s transition strategy

The goal is simple: turn listings into insight, and insight into strategy.

## ⚠️ Business Challenge

The dataset contained thousands of BMW listings with no immediate clarity on:

• Model dominance versus niche offerings

• Market growth cycles and external disruptions

• Customer preferences for fuel and transmission types

• Revenue and tax concentration risks

• Adoption gaps in electric and hybrid vehicles

Without structured analysis, decision-making around pricing, production focus, and electrification strategy would rely on assumptions rather than evidence.

## 📌 Project Objectives

This project aimed to:

• Clean and transform raw BMW listings using Power Query

• Analyze trends across models, years, fuel types, and transmissions

• Identify volume leaders, value drivers, and tax contributors

• Understand customer behavior and market readiness for Electrical vehicles(EVs)

• Build an interactive Power BI dashboard that communicates insights clearly

## 🏗️🔍 Data Preparation & EDA
### 🗂️ Dataset Overview

• Source: Kaggle 

• Records: BMW car listings across multiple years

• Key fields include:

o Model

o Year

o Fuel Type

o Transmission

o Price

o Tax

## 🧹 Data Cleaning & Preparation (Power Query)

• Standardized categorical fields (Model, Fuel Type, Transmission)

• Verified numeric fields (Price, Tax, Year)

• Removed inconsistencies and formatting errors

• Ensured clean model naming for accurate aggregation

• Prepared the dataset for reliable trend and distribution analysis

## 📝 Methodology
### 🔍 Exploratory Data Analysis

Using Power BI visuals and aggregations, analysis was conducted across:

• BMW model volume and value contribution

• Yearly listing trends

• Fuel type adoption

• Transmission preferences

• Tax contribution by model

This EDA phase formed the backbone of the final dashboard.

## 🖥️ Dashboard Development

• Built an interactive Power BI dashboard

• Used bar charts, line charts, donut charts, and KPI cards

• Focused on clarity, balance, and executive readability

• Designed visuals to support storytelling, not just reporting

<img width="880" height="503" alt="BMW_Dashboard " src="https://github.com/user-attachments/assets/c85a95a2-e287-4ca1-920e-a56114f7a8f8" />



## 💡 Dashboard & Key Insights
### 🚘 BMW Model Dominance

• 3 Series leads the dataset with 2,334 cars, making it the clear volume engine

• Least represented models:

o Z3 – 7 cars

o M6 – 8 cars

#### Insight:
The 3 Series is BMW’s backbone, balancing affordability and luxury, while models like the Z3 and M6 represent niche or legacy segments rather than growth drivers.

### 📈 How BMW Listings Changed Over Time

• Listings were low in earlier years

• Strong upward trend between 2017 and 2019

• Peak in 2019 with 3,396 listings

• Sharp decline in 2020 with 722 listings

What this really means:
The late-2010s surge reflects increased imports, stronger demand for used BMWs, and the rise of online car marketplaces.
The sudden drop in 2020 aligns directly with the COVID-19 pandemic, which disrupted supply chains and consumer activity.

This dip does not signal reduced brand interest, but rather temporary supply constraints that later pushed used BMW prices upward.

### ⛽ Fuel Type Distribution

• Diesel dominates at 65.53%

• Petrol remains strong

• Hybrids account for 2.79%

• Electric vehicles represent just 0.03%

#### Insight:
Diesel’s dominance shows that many markets still prioritize range and torque over electrification.
Hybrids act as a “security blanket” for customers with range anxiety, offering electric benefits without full dependency on charging infrastructure.
Full EV adoption remains limited, not due to product weakness, but infrastructure readiness.

### ⚙️ Transmission Preferences

• Semi-automatic: 43.48%

• Automatic: 33.21%

• Manual: 23.30%

#### Insight:
Customers are clearly choosing convenience and performance over mechanical control.
Modern semi-automatic systems shift faster than humans, making manuals increasingly niche despite lower maintenance costs.

#### 💰 Total Price Value by Model

• 3 Series contributes 19.97% of total price value

• Lowest contributors:

o i3 – 0.33%
o M2 – 0.37%
o i8 – 0.40%

#### Insight:
Volume directly drives value. The dominance of the 3 Series explains its leadership in total market value.

### 🧾 Tax Contribution by Model

• 3 Series accounts for 21.42% of total tax

• Lowest tax contributors:

o i8 – 0.10%

o i3 – 0.12%

o Z3 – 0.14%

### Insight:
The 3 Series effectively subsidizes BMW’s transition to electric, while government incentives successfully minimize tax burdens for i-series models.

## 💎 Key KPIs Displayed

* Maximum Car Price: $123.46K

* Average Tax: $131.60

* Average Fuel Efficiency (MPG): 56.48

* Average Engine Size: 2.2

## 🏁 Conclusion

• The BMW market is anchored by the 3 Series, which drives volume, value, and tax revenue

• Market activity peaked in 2019 before being disrupted by COVID-19

• Diesel remains dominant, highlighting infrastructure and range realities

• Hybrids outperform EVs as a transitional solution

• Manual transmissions are steadily losing relevance

• Electric models benefit from tax incentives but suffer from low adoption

Overall, the data reveals a brand in transition, balancing legacy demand with future electrification.

## 🚀 Recommendations

• Protect the 3 Series profit engine by introducing mild-hybrid variants to reduce tax burden while retaining familiarity

• Reduce hybrid manufacturing complexity to lower costs and increase adoption beyond the current 2.79%

• Lean into semi-automatic dominance, phasing out manuals for non-M models

• Accelerate EV adoption through charging incentives like home chargers or free public charging packages

• Use ICE-generated tax revenue strategically to support long-term electrification goals

## 🛠️ Tools Used

• Power Query

o Data cleaning and transformation

• Power BI

o Data modeling

o Interactive dashboards

o Business storytelling through visuals

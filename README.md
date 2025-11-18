# Case-Study---Homebuilder-Industry

# 🏠 Homebuilder Industry: Data Research & Predictive Analysis

**Author:** Muyang Ye  
📧 my624@georgetown.edu  

---

## 📘 Project Overview

This project provides a comprehensive analysis of the U.S. homebuilder industry, with a focus on understanding value chain dynamics, identifying key performance indicators (KPIs), and predicting future housing starts using quantitative models. Insights are tailored for investors, analysts, or strategists seeking data-driven perspectives on the sector.

---

## 🧠 Research Components

### **1. Industry Analysis**
- **Customers & Suppliers**: Breaks down the ecosystem: homebuyers, developers, investors, government entities, and materials providers.
- **Competition Mapping**: Assesses national public builders, regional private builders, and substitutes such as build-to-rent companies.
- **Key KPIs**: Highlights leading and lagging indicators like net new orders, housing starts, gross margin, and cash conversion.

### **2. Data Sources**
External data used includes:

- **FRED** (Federal Reserve Economic Data): Housing Starts, Mortgage Rates  
- **NAHB** (National Association of Home Builders): Builder Confidence Index  
- **Google Trends**: Demand proxy for "new homes"  
- **Company Filings**: Gross margins, ASP, backlog metrics  

---

## 🔮 Forecast Modeling

### **SARIMAX Model**
- **Goal**: Forecast U.S. Housing Starts (HOUST)  
- **Variables Included**:
  - Lagged Building Permits (strong positive correlation)
  - Mortgage Rates (negative influence)
 <img width="538" height="31" alt="image" src="https://github.com/user-attachments/assets/59910530-bdd0-4304-afab-6eb1faba1623" />

- **Outcome**:
  - Forecast: **~1.34 million starts** (Sep 2025)  
  - 95% Confidence Interval: **1.19M – 1.49M**
  
<img width="406" height="218" alt="image" src="https://github.com/user-attachments/assets/1872b1ce-c7ae-40ef-b4d1-2f02d5ec0c5b" />

### **Qualitative Forecast Inputs**
- Market sentiment (Builder Confidence Index: 32)
- Google Trends for "new homes"
- Mortgage rate shifts (down from recent highs)

---

## 📈 Key Findings

- Housing demand remains tempered by high mortgage rates, though recent declines have eased pressure.
- Building permits and backlog conversion rates are strong predictors of near-term housing starts.
- Large public builders retain competitive advantage through scale and data transparency.
  
---

## 🔧 Tools & Technologies

- Python (statsmodels, pandas, matplotlib)
- Jupyter Notebooks  
- SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous regressors)
- Industry APIs & open data sources

---

## 📄 Repository Structure



# 🌍 Global Forest Intelligence

## 📌 Project Overview

**Global Forest Intelligence** is a data analytics project focused on exploring global forest and tree-cover changes using prepared **Global Forest Watch** data.

The project analyzes tree cover loss across **226 countries from 2001 to 2025**, together with forest-loss drivers, carbon emissions and removals, primary forest loss, and urban tree biodiversity (GUTS).

---

## 🎯 Objectives

- Analyze global tree cover loss trends over time.
- Identify countries with the highest cumulative forest loss.
- Analyze the main drivers of tree cover loss.
- Examine forest carbon emissions and removals.
- Analyze tropical primary forest loss.
- Explore urban tree biodiversity.
- Perform data quality and structure analysis.
- Generate insights that can support forest monitoring and decision-making.

---

## 📊 Dataset

The project uses prepared **Global Forest Watch** data covering:

- **226 countries**
- **2001–2025**
- Tree Cover Loss
- Drivers of Loss
- Carbon Flux
- Primary Forest
- Urban Biodiversity (GUTS)
- Data Quality information

---

## 🛠️ Tools & Technologies

- Python
- Power BI
- Excel
- SQL
- Machine Learning
- Data Cleaning & EDA
- Data Visualization

---

## 📈 Key Findings

| Metric | Result |
|---|---:|
| Total Tree Cover Loss | **542.8M hectares** |
| Average Annual Loss | **21.71M hectares/year** |
| Highest-Loss Year | **2016** |
| Highest-Loss Year Value | **29.7M hectares** |
| Highest Cumulative Loss Country | **Russia** |
| Russia's Loss | **92.1M hectares** |
| Top 3 Countries Share | **43.7%** |
| Net Forest Carbon Flux | **-127.06 Gt CO2e** |
| Largest Classified Driver | **Permanent Agriculture – 31.8%** |
| Tropical Primary Forest Loss | **87.3M hectares** |
| First-to-Last Decade Change | **+50.1%** |
| GUTS Species Records | **23,340** |

---

## 📊 Data Analysis

### 1. Global Trend Analysis

Examining annual changes in tree cover loss between 2001 and 2025.

### 2. Country-Level Analysis

Comparing countries according to their cumulative tree cover loss.

### 3. Drivers of Forest Loss

Analyzing major causes of classified tree cover loss, including permanent agriculture.

### 4. Carbon Analysis

Analyzing forest carbon emissions, removals, and net carbon flux.

### 5. Primary Forest Analysis

Separating primary forest loss from other forest-loss indicators.

### 6. Urban Biodiversity

Analyzing GUTS urban tree biodiversity data separately from natural forest datasets.

---

## 🤖 Machine Learning

The project includes a dedicated Machine Learning component for forest-related predictive analysis.

The ML workflow is organized separately from the Power BI analytics and EDA components.

---

## 📊 Power BI

The project includes Power BI dashboards designed to transform processed forest data into interactive visual insights.

---

## 🔍 Data Quality

A data-quality audit was performed across the main datasets to identify:

- Missing values
- Duplicate records
- Number of rows and columns
- Table structure
- Data consistency

The project also distinguishes between country-level and subnational data quality.

---

## 💡 Recommendations

Based on the analysis:

- Prioritize short-term forest-loss prediction using ML-ready data.
- Focus monitoring and intervention on countries with major forest-loss patterns.
- Include climate variables such as heat and drought in future predictive models.
- Track annual net forest carbon flux.
- Analyze primary forests separately from secondary forests.
- Keep urban biodiversity data analytically separate from natural forest datasets.

---

## 📁 Repository Contents

```text
GLOBAL-FOREST-INTELLIGENCE/
│
├── 01_SOURCE_PRESERVED/
│
├── 03_POWERBI_ANALYTICS.zip
│
├── Global_Forest_Intelligence_EDA.html
│
├── forest_loss_model.zip
│
├── tree analytics.pbix
│
└── README.md

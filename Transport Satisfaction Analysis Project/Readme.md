# 🚍 Transportation Satisfaction Dashboard  
### Public Universities of Bangladesh

An interactive multi-page Excel dashboard analyzing transportation experience of students and teachers across public universities in Bangladesh.

---

## 📌 Project Overview

This project explores commuting patterns, transport costs, infrastructure perception, environmental conditions, and overall satisfaction using survey data (1100+ responses).

The goal was to transform raw survey data into structured insights through data cleaning, transformation, and interactive visualization.

The dashboard was:

- 🖌 Initially designed in **Figma** (layout & visual structure)
- 📊 Implemented in **Microsoft Excel**
- 🔄 Cleaned & transformed using **Power Query**
- 📈 Built using Pivot Tables, Calculated Fields & Slicers

---

## 🧠 Key Features

### 1️⃣ Executive KPI Summary
- Total Respondents
- Satisfaction Rate (%)
- Average Travel Time
- Average Daily Cost
- Overall Transport Score

---

### 2️⃣ Profile & Accessibility
- Gender distribution
- Student vs Teacher breakdown
- Transportation cost distribution
- Ease of access vs road connectivity comparison

---

### 3️⃣ Travel Behavior Analysis
- Average travel time (going vs returning)
- Travel frequency distribution
- Multi-modal transport usage analysis
- University-wise commuting insights

---

### 4️⃣ Infrastructure & Safety Scorecard
- Road signs visibility
- Road layout convenience
- Ride smoothness
- Vehicle safety features
- Driver behavior
- Vehicle speed
- Social security perception

---

### 5️⃣ Environment & Traffic Management
- Noise levels
- Dust conditions
- Road condition (rain/winter)
- Traffic rule enforcement
- Traffic flow & jam control
- Emergency access

---

## 🔄 Data Processing Approach

### ✔ Multi-Response Handling (Transport Modes)

Survey responses allowed multiple transport modes per respondent.

To preserve accuracy:

- Split transport modes into rows (Power Query)
- Applied one-hot encoding (binary indicator columns)
- Aggregated mode usage using Pivot Tables

---

### ✔ Categorical to Numeric Conversion

Cost and time ranges were converted using midpoint calculation for numerical analysis:

Example:
- `50–100` → `75`
- `100–150` → `125`

---

### ✔ Calculated Metrics

- Transport Score (average of perception-based indicators)
- Commute Burden Index (time + cost factors)
- Satisfaction percentage
- Mode usage frequency

---

## 🛠 Tools & Technologies Used

- Microsoft Excel
- Power Query
- Pivot Tables
- GETPIVOTDATA formulas
- Slicers (interactive filtering)
- Figma (UI/UX layout design)

---

## 🎯 Challenges Faced

- Handling multi-select survey responses
- Converting categorical ranges into numeric form
- Maintaining clean dashboard hierarchy
- Designing multi-page structure without clutter
- Ensuring slicer consistency across all pivot tables

---

## 📊 Insights Generated

- Most commonly used transport modes
- Universities with higher/lower satisfaction rates
- Infrastructure & safety perception trends
- Environmental impact on commuter experience
- Frequency-based commuting patterns

---

## 🚀 Future Improvements

- Add time-series capability
- Build Power BI version
- Export executive PDF summary
- Develop web-based dashboard version

---

## 👤 Author

**Arnab Aich**  
Mathematics Student | Aspiring Data Scientist  
Data Analyst at Brain Machine AI  

🔗 LinkedIn: https://linkedin.com/in/arnab-aich/

---

## ⭐ If You Found This Useful

Consider giving the repository a star ⭐  
Feedback and suggestions are welcome!

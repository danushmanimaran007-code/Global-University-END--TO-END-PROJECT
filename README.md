# 🎓 University Success Analysis

A comprehensive Power BI report analyzing global university performance across country distribution, rankings, student enrollment trends, and demographic insights.

---

## 📊 Dashboard Overview

The report is structured into four core analysis sections:

| Section | Description |
|---|---|
| **Country Analysis** | University distribution, international & female student enrollment by country |
| **University Analysis** | Performance metrics, student-staff ratios, and institutional comparisons |
| **Ranking Analysis** | Insights across three major ranking systems and their criteria |
| **Yearly Analysis** | Enrollment and ranking trends from 2005 to 2016 |

---

## 🗂️ Report Pages

### 1. Country Analysis
- Country-wise university count (USA leads with **273** universities)
- Total international students by country (**4.78M** globally)
- Total female student enrollment by country (**12.02M** globally)
- University ranking count by country
- Total student count by country

### 2. University Analysis
- University performance by ranking system
- University score vs. total international student correlation (**0.59**)
- Top universities by total student enrollment
- Student-staff ratio analysis by institution
- Percentage of international students by university
- Ranking criteria vs. student-staff ratio correlation (**0.74**)

### 3. Ranking Analysis
- Three ranking systems compared:
  - **Center for World University Rankings** — 1,024 universities
  - **Times Higher Education World University Ranking** — 245 universities
  - **Shanghai Ranking** — 93 universities
- Average scores by ranking system (CWUR: **328.17**, THE: **59.14**, Shanghai: **35.29**)
- Female student percentage by ranking system
- Total international students by ranking system
- Ranking score vs. female student percentage correlation (**0.62**)
- Best year: **2016** | Top country: **Argentina**

### 4. Yearly Analysis
- Annual enrollment trends (2005–2016)
- International student enrollment growth: **1.58M (2005) → 4.76M (2015)**
- Female student enrollment growth: **4.1M (2006) → 12.0M (2015)**
- Total university count growth over the years
- Score vs. student-staff ratio correlation over time (**0.62**)

---

## 🔑 Key Insights

- 🇺🇸 The **United States** dominates global higher education — most universities (273), highest international student intake (1.48M), and highest female enrollment (~4.93M).
- 📈 International student enrollment grew **steadily from 2005 to 2015**, then experienced a sharp drop in 2016.
- 🏫 **Arizona State University** has the highest total student enrollment (499,416).
- 🌍 **École Polytechnique Fédérale de Lausanne** attracts the highest percentage of international students.
- 🏆 The **Center for World University Rankings** covers the most universities and holds the highest aggregate ranking score.
- 👩‍🎓 Female students show a higher preference for universities ranked by **Times Higher Education**.
- 📊 A strong positive correlation (**0.74**) exists between university ranking criteria and student-staff ratio.

---

## ❓ Research Questions Addressed

The report answers **27 analytical questions**, including:

1. How many universities are there in each country?
2. What is the distribution of international students across countries?
3. Which country has the highest female student enrollment?
4. How many universities are ranked by each ranking system?
5. What is the average score by ranking system?
6. How does ranking affect student-staff ratio?
7. What are the most important criteria by ranking system?
8. Is there a correlation between university score and international students?
9. How does female student percentage impact rankings?
10. Which university has the highest enrollment?
11. How has international student enrollment changed over the years?
12. What are the trends in female student enrollment over time?
...and more.

---

## 🛠️ Tools & Technologies

- **Visualization:** Microsoft Power BI Desktop
- **Data Coverage:** Global universities across 60+ countries
- **Time Period:** 2005 – 2016
- **Ranking Systems:** CWUR, Times Higher Education, Shanghai Ranking

---

## 📁 Repository Structure

```
├── PowerBI_report.pdf       # Exported report (PDF format)
├── UniversityAnalysis.pbix  # Power BI Desktop file (if applicable)
├── data/                    # Source datasets (if applicable)
│   └── universities.csv
└── README.md
```

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/university-success-analysis.git
   ```
2. Open `UniversityAnalysis.pbix` in **Power BI Desktop**.
3. Refresh the data source if you have the underlying dataset.
4. Navigate through the four report tabs to explore the analysis.

---

## 📌 Notes

- All student figures are aggregated across available ranked universities and may not represent entire national enrollment.
- The 2016 data shows a decline across multiple metrics; this may be attributed to data availability or reporting changes rather than actual trends.

---

## 📄 License

This project is open for educational and analytical purposes. Please credit appropriately if reused or extended.

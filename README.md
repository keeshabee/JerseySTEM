# MySTEMClub@PublicLibraries Expansion Analysis

> Data-Driven Site Selection for STEM Education Program Expansion Across New Jersey

![Project Dashboard](portfolio_project_snapshot.png)

---

## 📊 Project Overview

As **Deputy Data Analytics Lead** at JerseyStem, I led a comprehensive analysis to identify optimal locations for expanding STEM education programs across New Jersey. The project integrated **Salesforce CRM data** with **NJ Department of Education records** to pinpoint public libraries in communities with Title I middle schools.

### Key Challenge

Inconsistent data formatting between Salesforce and NJ DOE systems prevented direct matching. I developed a **custom standardization algorithm** to enable accurate integration of 468 libraries with 934 schools.

---

## 🎯 Key Metrics

| Metric | Value |
|--------|-------|
| **Libraries Analyzed** | 468 |
| **Optimal Locations Identified** | 88 |
| **Title I Schools Assessed** | 934 |
| **Students Reachable** | 10,000+ |
| **Priority Cities** | 5 |

---

## 🛠️ Technical Stack

- **Languages:** Python (Pandas, NumPy, Matplotlib)
- **Databases:** MySQL
- **Data Sources:** Salesforce CRM, NJ Department of Education
- **Analysis Tools:** Excel (Advanced formulas, dashboards)
- **Data Integration:** Custom ETL pipeline

---

## 🔍 Technical Approach

1. **Data Extraction**
   - Extracted 468 libraries from Salesforce MySQL database
   - Queried NJ DOE datasets for 965 middle schools (2023-2024)

2. **Data Standardization**
   - Developed city name standardization algorithm
   - Resolved NCES code format inconsistencies
   - Created unified geographic matching system

3. **Title I Identification**
   - Analyzed 934 middle schools for Title I status
   - Built custom scoring algorithm (0-100 scale)
   - Identified 277 priority schools (106 confirmed, 171 high likelihood)

4. **Priority Scoring**
   - **Priority Score:** Title I school concentration (0-600+)
   - **Proximity Score:** Same-city matching for walkability (0-500+)
   - **Combined Score:** Weighted ranking (60% concentration + 40% proximity)

5. **Dashboard Creation**
   - Built 5-worksheet Excel analysis with formatting
   - Created color-coded priority rankings
   - Automated calculations and data validation

---

## 📈 Key Deliverables

✅ **Comprehensive Excel Analysis** (5 analytical worksheets)
- All Libraries Ranked
- Optimal Same-City Locations
- Top 25 Immediate Priorities  
- High Priority Libraries
- City-Level Outreach Plan

✅ **Strategic Recommendations**
- Identified 88 libraries in same cities as Title I schools
- Prioritized top 25 locations for immediate outreach
- Created phased expansion roadmap

✅ **Executive Summary**
- Stakeholder communication materials
- Methodology documentation
- Impact projections

---

## 💼 Business Impact

### Top 5 Priority Cities

| City | County | Title I Schools | Students | Libraries |
|------|--------|----------------|-----------|-----------|
| **Paterson** | Passaic | 14 | 2,086 | 2 |
| **Newark** | Essex | 12 | 981 | 11 |
| **Trenton** | Mercer | 9 | 1,401 | 5 |
| **Jersey City** | Hudson | 11 | 1,914 | 14 |
| **Elizabeth** | Union | 8 | 1,270 | 4 |

### Estimated Impact

If all 88 optimal library locations engage, JerseyStem could establish STEM programming in communities serving **10,000+ economically disadvantaged middle school students** across New Jersey's highest-need areas.

---

## 🎨 Methodology Highlights

### Title I School Identification Scoring

**Confirmed Title I (Score: 100)**
- Schools with CSI/TSI/ATSI accountability designation
- 100% verified by NJ Department of Education

**High Likelihood (Score: 60-99)**
- 60+ economically disadvantaged students
- <40% proficiency rates
- Multiple validation factors

### Priority Ranking Algorithm

```python
# Simplified algorithm logic
Priority_Score = (
    (title1_count * 20) +
    (multiple_school_bonus) +
    (confirmed_schools * 15) +
    (high_student_count_bonus)
)

Proximity_Score = (
    (confirmed_same_city * 30) +
    (high_likelihood_same_city * 20)
)

Combined_Score = (Priority_Score * 0.6) + (Proximity_Score * 0.4)
```

---

## 📁 Project Files

- **Library_Title1_Priority_Analysis_Final.xlsx** - Complete analysis with 5 worksheets
- **NJ_Title1_Middle_Schools_Analysis.xlsx** - Title I school assessment
- **Email_to_Nabil_Library_Analysis.txt** - Stakeholder communication
- **Scoring_System_Explanation.txt** - Methodology documentation
- **Project_Completion_Summary.txt** - Full project overview

---

## 🚀 Skills Demonstrated

- **Data Integration:** Successfully merged disparate data sources (CRM + government databases)
- **Problem Solving:** Resolved data quality issues through custom standardization
- **Statistical Analysis:** Developed multi-factor scoring algorithms
- **Database Management:** MySQL queries and optimization
- **Data Visualization:** Created professional Excel dashboards
- **Stakeholder Communication:** Translated technical analysis into actionable recommendations
- **Project Management:** Delivered complete analysis on schedule with clear documentation

---

## 🔗 Links

- 📊 [View Full Analysis](#) *(Link to Excel file or live dashboard)*
- 📄 [Download Report](#) *(Link to PDF summary)*
- 💻 [View Code on GitHub](#) *(Link to code repository)*
- 🌐 [JerseyStem Website](https://www.jerseystem.org)

---

## 📝 Project Timeline

- **Duration:** 3 weeks
- **Role:** Deputy Data Analytics Lead
- **Organization:** JerseyStem (Volunteer)
- **Status:** ✅ Complete - Ready for implementation

---

## 🎓 For Recruiters

This project demonstrates proficiency in:
- **Business Intelligence:** End-to-end data analysis pipeline
- **Data Analytics:** Large-scale dataset processing (1,400+ records)
- **Technical Skills:** Python, SQL, Excel, Salesforce integration
- **Strategic Thinking:** Translating data insights into actionable strategy
- **Communication:** Executive-level reporting and documentation

**Estimated Hours:** ~20 hours of analysis, documentation, and stakeholder communication

---

## 📧 Contact

**Rigel** - [Your Email] | [LinkedIn] | [Portfolio Website]

*This project was completed as part of volunteer work with JerseyStem, a non-profit organization expanding STEM education access across New Jersey.*

---

## 📜 License

Project data and methodology © JerseyStem. This portfolio entry is for demonstration purposes.

---

**Tags:** `Data Analytics` `Python` `MySQL` `Business Intelligence` `Excel` `Salesforce` `Non-Profit` `Education` `Strategic Planning`

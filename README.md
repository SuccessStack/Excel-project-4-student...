
# 🎓 Student Performance Analysis | Excel Project

Welcome to the **Student Performance Analysis Dashboard**!  
This project explores student academic trends, personal factors, and lifestyle influences on grades using structured school report data. The goal is to extract **meaningful educational insights** using **Excel-based PivotTables** and charts.

---

## 🎯 Project Objective

The aim of this analysis is to understand:
- How student background and habits impact academic performance
- What social or family factors correlate with grade improvement or decline
- Where educational support should be targeted for better outcomes

---

## 🧾 Dataset Description

The dataset was sourced from the **UCI Machine Learning Repository**, and covers two secondary schools in Portugal. Each record represents one student, and contains 33 attributes including:

### Key Fields:
- **G1, G2, G3**: 1st, 2nd, and Final period grades
- **sex**: Gender of the student
- **age**: Age in years
- **studytime**: Weekly study time
- **failures**: Past class failures
- **absences**: Number of absences
- **school, address, famsize**: School and family info
- **internet, romantic, paid**: Access to resources and relationships
- **freetime, goout, Dalc, Walc**: Social habits and alcohol use

---
![image](https://github.com/user-attachments/assets/f60f3706-21a5-450e-af75-3c2ffc450e91)
---


## 📊 Dashboard Features (Built in Excel with PivotTables)

### 📈 Academic Performance Insights
| Pivot Title | Rows | Columns | Values | Purpose |
|-------------|------|---------|--------|---------|
| G1–G3 by Gender and Study Time | sex | studytime | Avg of G1–G3 | Study habits by gender |
| G1–G3 by School and Internet | school | internet | Avg of G1–G3 | School performance with/without tech |
| G1–G3 by Failures and Mother's Education | failures | Medu | Avg of G1–G3 | Academic struggles vs parent background |
| G1–G3 by Romantic & Social Life | romantic | goout | Avg of G1–G3 | Lifestyle impact |
| Average of G1–G3 by Gender and School | sex | school | Avg of G1–G3 | Gender trends in schools |
| G1–G3 by Study Time and Failures | studytime | failures | Avg of G1–G3 | Do more hours help offset failure history? |
| Average of G1–G3 by Internet & Extra Classes | internet | paid | Avg of G1–G3 | Tech + tutoring |
| G1–G3 by Family Size & Guardian | famsize | guardian | Avg of G1–G3 | Home support patterns |

---

## 🔍 Key Insights

1. **Study Time Matters**  
   Students who studied ≥10 hours per week consistently scored higher in all grade periods.

2. **Failures Impact G3**  
   Past failures strongly correlate with lower final grades, even with improved G2.

3. **Romantic Relationships & Go-Out Frequency**  
   Higher social activity often showed a slight decline in G3 performance.

4. **Internet Access**  
   Students with home internet showed better grade retention from G2 to G3.

5. **Mother’s Education (Medu)**  
   Higher maternal education levels often matched with better grades, especially in G1 and G2.

---

## 🧠 Methodology

### ✅ Data Cleaning
- Checked for nulls and inconsistencies
- Created new columns:
  - Average

### ✅ Tools Used
- **Microsoft Excel** (main analysis tool)
- PivotTables (with multi-row, multi-column setups)
- Conditional Formatting (highlighted grade bands)
- Slicers (to filter by gender, school, support)
- Optional: Exported to Power BI for interactive visuals

---

## 🚀 How to Use This Project

1. Open the provided Excel workbook.
2. Go to the **Raw_Data** sheet for student-level data.
3. Explore **PivotSheets** for grouped insights.
4. View the **Dashboard** sheet for a visual summary.
5. Use **slicers and filters** to dive into specific student segments.

---

## 🙏 Acknowledgments

- Dataset provided by **UCI Machine Learning Repository**  
- Based on academic work by Cortez and Silva (2008)  
- Thanks to Microsoft Excel for enabling accessible data analysis for educators, researchers, and students worldwide.

# 📊 HR Employee Attrition Analysis

An interactive **Power BI** dashboard that explores why employees leave an organization. It covers **1,470 employees** across three departments and breaks attrition down by demographics, job role, satisfaction, commute, promotion history, overtime, and compensation.

> **Built with:** Power BI Desktop  
> **Project type:** HR Analytics / Data Visualization  
> **Dashboard pages:** 3

---

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Business Questions](#-business-questions)
- [Dataset](#-dataset)
- [Dashboard Pages](#-dashboard-pages)
- [Key Insights](#-key-insights)
- [Recommendations](#-recommendations)
- [Tools & Skills Demonstrated](#-tools--skills-demonstrated)
- [Repository Structure](#-repository-structure)
- [How to Use](#-how-to-use)
- [Author](#-author)

---

## 🎯 Project Overview

Employee attrition is costly: it drives up hiring and training expenses and disrupts team productivity. This project analyzes an HR dataset to identify **who is leaving, where, and what factors are associated with their departure**, so that HR teams can act on retention before it becomes a problem.

**Headline KPIs**

| Metric | Value |
|---|---|
| Total Employees | 1,470 |
| Attrition Rate | 16.1% |
| Attrition Count | 237 |
| Average Distance From Home | 9 |
| Average Monthly Income | $6,502.9 |
| Average Daily Rate | $802.5 |

---

## ❓ Business Questions

This dashboard was designed to answer:

1. What is the overall attrition rate, and how does it differ by gender and marital status?
2. Which job roles lose the most employees?
3. Does job satisfaction affect whether people leave?
4. Do commute distance and time since last promotion play a role?
5. How do overtime, work-life balance, and pay relate to attrition?
6. What does the workforce look like by department, role, age, education, and performance?

---

## 🗂 Dataset

- **Records:** 1,470 employees
- **Departments:** Research & Development (961), Sales (446), Human Resources (63)
- **Attributes include:** Age, Gender, Marital Status, Department, Job Role, Job Satisfaction, Work-Life Balance, Performance Rating, Monthly Income, Daily Rate, Overtime, Distance From Home, Years Since Last Promotion, Business Travel, Education Level & Field, Attrition (Yes/No)

> 📝 *Add your data source here (e.g., Kaggle / IBM HR Analytics dataset) and a link if applicable.*

---

## 🖥 Dashboard Pages

### Page 1 – Attrition Overview
Focuses on **who is leaving** and the factors linked to it.

- KPI cards: Attrition Rate, Attrition Count, Total Attrition Years, Average Distance From Home
- Attrition Rate by Gender
- Attrition Count by Marital Status
- Attrition Rate by Job Role
- Attrition Rate by Last Promotion in Years
- Attrition Rate by Job Satisfaction
- Attrition Rate by Distance From Home

### Page 2 – Overtime & Work-Life Analysis
Focuses on **workload, overtime pay, and demographics**.

- KPI cards: Average Overtime Monthly Rate ($14.3K), Average Overtime Hourly Rate ($66), Total Years With Company, Number of Companies Worked
- Overtime Hourly Rate by Age and Attrition
- Attrition Rate by Over Time and Work-Life Balance
- Overtime Monthly Rate by Job Role and Over Time (treemap)
- Overtime Monthly Rate by Job Satisfaction
- Over Time by Gender
- Age Distribution

### Page 3 – Workforce Profile
Focuses on **the makeup of the organization**.

- KPI cards: Average Monthly Income, Employee Age, Average Daily Rate, Total Employees
- Employee Performance Rating by Job Role
- Job Satisfaction Rating by Job Role
- Total Employees by Department
- Monthly Income by Job Role and Business Travel
- Business Travel by Department
- Job Role by Education Level and Education Field

---

## 🔍 Key Insights

- **Overall attrition is 16.1%**, which is 237 of 1,470 employees.
- **Men leave at a higher rate than women**: 17.0% vs. 14.8%.
- **Single employees account for the most exits** (120), followed by married (84) and divorced (33) employees.
- **Sales Representatives have by far the highest attrition rate**, at roughly 40%. Laboratory Technicians, Human Resources, and Sales Executives follow. Healthcare Representatives and Manufacturing Directors have the lowest.
- **Lower job satisfaction goes with higher attrition**: the rate falls from about 23% at satisfaction level 1 to about 11% at level 4.
- **Longer commutes tend to coincide with higher attrition**, with the rate climbing noticeably beyond roughly 10 units of distance and spiking at the longest distances.
- **Time since last promotion shows a volatile pattern**: attrition dips around 5 years and peaks around 9 years since promotion.
- **Performance ratings are concentrated at 3 and 4** (1,244 and 226 employees respectively).
- **Workforce is concentrated in R&D** (961 employees), with Sales at 446 and HR at 63.
- **Age distribution peaks in the early-to-mid 30s**, with the workforce spanning roughly ages 18 to 60.

---

## 💡 Recommendations

Based on the patterns above, HR teams could consider:

1. **Target retention in Sales Representative roles** through compensation review, career pathing, and manager check-ins.
2. **Improve job satisfaction** with regular pulse surveys, since low satisfaction is clearly tied to higher attrition.
3. **Support employees with long commutes** via remote or hybrid options, or commuter benefits.
4. **Review promotion cycles** to make sure long-tenured employees without recent promotions have a visible growth path.
5. **Monitor overtime and work-life balance**, especially in roles with heavy overtime.
6. **Engage early-career and single employees**, who make up the largest share of exits, with mentoring and development programs.

---

## 🛠 Tools & Skills Demonstrated

- **Power BI Desktop**: report design, KPI cards, interactive visuals
- **Data modeling & DAX**: calculated measures such as attrition rate, averages, and counts
- **Data visualization**: pie/donut charts, bar charts, line charts, treemaps, ribbon charts, histograms, matrix tables
- **HR analytics**: attrition, satisfaction, compensation, and workforce analysis
- **Dashboard storytelling**: turning raw data into actionable insights

---

## 📁 Repository Structure

```
├── HR_Attrition_Dashboard.pbix        # Power BI report file
├── Employee_Attrition_Analysis.pdf    # Exported dashboard (PDF)
├── data/
│   └── HR_Attrition_Data.csv          # Dataset
├── images/
│   ├── page1_overview.png             # Dashboard screenshots
│   ├── page2_overtime.png
│   └── page3_workforce.png
└── README.md
```

---

## 🚀 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. **Open the report**: open the `.pbix` file in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows).
3. **Refresh the data** if needed: *Home → Transform data → Data source settings*, and point to the dataset in the `data/` folder.
4. **Explore**: use slicers, hover tooltips, and cross-filtering to dig into the data.

Or just browse the PDF export or screenshots in the `images/` folder.

---

## 📸 Dashboard Preview

| Page 1 – Attrition Overview | Page 2 – Overtime & Work-Life |
|---|---|
| ![Page 1](images/page1_overview.png) | ![Page 2](images/page2_overtime.png) |

| Page 3 – Workforce Profile |
|---|
| ![Page 3](images/page3_workforce.png) |

---

## 👤 Author

**Ebunoluwa Olaleye**  
🔗 [LinkedIn](https://linkedin.com/in/your-profile) · 💻 [GitHub](https://github.com/your-username) · 📧 sanusiebunolu@gmail.com[HR_Attritionproject_PBI.pdf](https://github.com/user-attachments/files/33305048/HR_Attritionproject_PBI.pdf)


*Created as part of a data analytics project with MeriSKILL.*

---

⭐ If you found this project useful, consider giving the repo a star!

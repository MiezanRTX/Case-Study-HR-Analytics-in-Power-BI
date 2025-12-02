# Case-Study-HR-Analytics-in-Power-BI

## Creating a cohesive report
### Keypoints
- Insights uncovered
    
# 📊 HR Analytics Power BI Report  
*Comprehensive Documentation & Insights (Markdown Version)*  
*Based on HR Analytics PBI – PDF Version*  
*(All insights refer to visuals extracted from the uploaded PDF)*

---

## 🏛 Executive Summary

The HR Analytics Dashboard provides a strategic overview of workforce composition, hiring activity, employee demographics, and attrition trends.  
The company has **1,470 total employees**, with **1,233 active** and **237 inactive**, resulting in an **attrition rate of 16.1%** (Page 1).

A critical insight is that **attrition is heavily concentrated among employees with low tenure**, especially those in high-pressure roles such as **Sales Executives**, **Research Scientists**, and **Laboratory Technicians**. Employees who travel often and those who work overtime show significantly higher attrition rates (Page 5).

Employee satisfaction metrics (Environment, Job Satisfaction, Manager Rating, Relationship Satisfaction) have **declined between 2020–2022**, signaling potential cultural, managerial, or workload challenges (Page 4).

Overall, the report highlights the need for **better onboarding**, **work-life balance initiatives**, **managerial development**, and **targeted retention strategies**.

---

# 1. 📁 Report Overview

Key KPIs (Page 1):

| KPI | Value |
|-----|-------|
| **Total Employees** | 1,470 |
| **Active Employees** | 1,233 |
| **Inactive Employees** | 237 |
| **Overall Attrition Rate** | **16.1%** |

---

# 2. 📚 Data Insights

## 2.1 Workforce Distribution

### **By Department**  
(From Page 1 – “Active Employees by Department”)

- Largest department: **Technology**  
- Followed by: **Sales** and **Human Resources**

### **By Age Group**  
(Page 2 – “Employees By Age”)

- **20–29 years** → Largest age bracket  
- **30–39 years** → Second largest  
- Under 20 → Very small group  
- Gender distribution generally balanced (Male, Female, Non-Binary, Prefer Not to Say)

---

# 3. 📉 Attrition Insights

## 3.1 Attrition by Job Role  
(Page 1 – “Active Employees by Job Role”)

Roles with high workforce concentration (and likely high attrition):

1. Sales Executive  
2. Research Scientist  
3. Laboratory Technician  
4. Manufacturing Director  
5. Sales Representative  

These roles are typically high-stress, high-turnover positions.

---

## 3.2 Attrition by Tenure (Years at Company)  
(Page 5)

- **Highest attrition happens in Years 0–2**  
- Attrition drops significantly after 4+ years  
- Very low attrition for employees with 10+ years

**Interpretation:** Early-tenure employees are leaving the fastest, indicating onboarding or job-expectation issues.

---

## 3.3 Attrition by Business Travel  
(Page 5 – “Total Employees & % Attrition by BusinessTravel”)

- **Frequent Travel** → Highest attrition  
- **Some Travel** → Moderate  
- **No Travel** → Lowest attrition

**Interpretation:** Travel burden likely drives turnover.

---

## 3.4 Attrition by Overtime  
(Page 5 – “% Attrition Rate by Overtime”)

- Overtime workers have **significantly higher attrition** vs non-overtime employees.

**Interpretation:** Burnout risk is real.

---

# 4. 💰 Salary & Demographic Insights

(Page 3)

## 4.1 Average Salary  
- **$113K** average annual salary

## 4.2 Ethnicity Distribution & Salary  
(Page 3 – “Total Employees and Average Salary by Ethnicity”)

- Majority ethnicity: **White**  
- **Asian** employees show competitive salary averages  
- Some minority groups have low representation

## 4.3 Marital Status  
(Page 3 – Pie Chart)

- **Single:** ~52%  
- **Married:** ~42%  
- **Divorced:** ~6%

Useful for benefits & HR policy planning.

---

# 5. 😊 Employee Satisfaction Trends  
(Page 4 – Satisfaction Time Series: 2020–2022)

Metrics showing decline:

- Job Satisfaction  
- Environment Satisfaction  
- Relationship Satisfaction  
- Manager Rating  
- Work-Life Balance  

**Interpretation:**  
Cultural health is deteriorating. This correlates with attrition spikes.

---

# 6. 🧭 Key Findings (Concise Highlights)

### 🔥 1. Early Tenure = Highest Attrition  
Employees with under 3 years of service leave the fastest.

### 🔥 2. Overtime Strongly Predicts Attrition  
Workload imbalance strongly affects retention.

### 🔥 3. Frequent Business Travel Increases Turnover  
Employees who travel often suffer burnout.

### 🔥 4. Declining Employee Satisfaction (2020–2022)  
Signals culture/managerial issues.

### 🔥 5. High-Risk Roles  
Sales, Research, and Lab roles experience more turnover.

---

# 7. 🎯 Actionable Recommendations

### **1. Improve Onboarding & Early Career Support**
- Structured 30–60–90 day plan  
- Assign mentors  
- Better expectation setting

### **2. Reduce Overtime via Workforce Planning**
- Reallocate workload  
- Increase staffing where required  
- Implement overtime approval controls

### **3. Rework Business Travel Policies**
- Reduce travel frequency  
- Improve travel compensation  
- Implement hybrid/remote alternatives

### **4. Strengthen Manager Training**
- Leadership development  
- Communication workshops  
- Anonymous employee feedback cycles

### **5. Targeted Retention Programs for High-Turnover Roles**
- Sales incentives  
- R&D development paths  
- Specialist career ladders

---

# 8. 📦 Suggested GitHub Repository Structure

```plaintext
HR-Analytics-PowerBI/
│
├── README.md                 # This markdown document
├── HR_Analytics.pbix         # Original PBIX file
├── pdf-report/               
│   └── HR Analytics PBI - PDF Version.pdf
├── images/                  
│   ├── page1.png
│   ├── page2.png
│   ├── page3.png
│   ├── page4.png
│   └── page5.png
└── data-dictionary/
    └── fields.md             # Optional schema/documentation

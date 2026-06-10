# HR People Analytics Dashboard

> An end-to-end people analytics project that turns raw HR workforce data into an executive Tableau dashboard, then translates the findings into a business presentation with clear insights and recommended actions.

---

## 1. Project Links

### Interactive Dashboard

Add your Tableau Public link here after publishing:

**Tableau Public:** https://public.tableau.com/app/profile/dang.khoa.nguyen3045/viz/HR_Attrition_Analysis_Dashboard/Dashboard1?publish=yes 

### Dashboard Preview

<img width="1605" height="952" alt="HR_Dashboard" src="https://github.com/user-attachments/assets/a59942e4-fa3d-4378-868e-58dc01807879" />


### Presentation Deck

<img width="2088" height="1176" alt="image" src="https://github.com/user-attachments/assets/b8741d3b-fb17-4bce-9017-c0a6fc0cc67c" />
<img width="2027" height="1151" alt="image" src="https://github.com/user-attachments/assets/0c373875-3eb1-45f8-ba38-e218ae0e72fd" />
<img width="2085" height="1178" alt="image" src="https://github.com/user-attachments/assets/a2b48043-7807-44c7-9978-4e9a676edf00" />
<img width="2092" height="1182" alt="image" src="https://github.com/user-attachments/assets/e8f107b7-800d-475f-abdb-8cecdc45b2f9" />
<img width="2086" height="1174" alt="image" src="https://github.com/user-attachments/assets/73897b2c-2656-441f-bee6-0c1226a791df" /> 
<img width="2092" height="1184" alt="image" src="https://github.com/user-attachments/assets/23301ab0-9a93-43f0-a339-8ed59eda625b" />

---

## 2. Project Background

People-related risks are often reported separately across HR files, spreadsheets, and static reports. This makes it difficult for decision-makers to understand how attrition, workforce composition, career progression, salary distribution, training, absence, and employee satisfaction are connected.

This project was built to solve that problem by creating a single HR People Analytics Dashboard that helps leaders monitor workforce health, identify people risks, and prioritise action.

The final dashboard was designed for:

* HR managers
* Workforce planning teams
* Diversity and inclusion teams
* Senior business leaders
* People and culture decision-makers

---

## 3. Business Problem

The main business problem was:

**How can HR leaders identify workforce risk and make better decisions when people data is spread across multiple indicators such as attrition, demographics, salary, training, absence, and satisfaction?**

To answer this, I developed a dashboard that connects workforce KPIs with deeper diagnostic views. Instead of only reporting numbers, the dashboard is designed to explain where the risk is concentrated and what action should be taken.

---

## 4. My Data Analysis Workflow

This project followed a full data analytics workflow from raw data exploration to dashboard storytelling.

### Step 1: Understand the Business Context

I started by defining the purpose of the dashboard and the key decisions it needed to support. The goal was not just to visualise HR data, but to help leaders answer practical workforce questions such as:

* Which roles have higher attrition risk?
* Is employee experience strong or only moderate?
* Are career progression patterns showing signs of stagnation?
* Does salary distribution require deeper pay equity review?
* Is training activity translating into better workforce outcomes?

### Step 2: Exploratory Data Analysis in Python

I used Python to perform exploratory data analysis before building the dashboard. This helped me understand the structure, quality, and meaning of the dataset.

The EDA process included:

* Inspecting columns, data types, and missing values
* Checking employee counts and active/terminated status
* Reviewing attrition patterns across job roles and departments
* Analysing salary bands, job levels, education, gender, and age groups
* Creating career-related groupings such as tenure bands and promotion bands
* Reviewing satisfaction and people experience score distributions
* Identifying which variables would be useful for Tableau visualisation

### Step 3: Data Cleaning and Preparation

After the EDA stage, I cleaned and prepared the dataset for Tableau.

The preparation process included:

* Standardising field names
* Creating grouped categories such as age bands, salary bands, and career bands
* Preparing calculated fields for active employees, total attrition, and attrition rate
* Checking that employee counts used distinct counting where required
* Reshaping selected fields for heatmap-style analysis
* Exporting the cleaned dataset for dashboard development
<img width="1114" height="1261" alt="image" src="https://github.com/user-attachments/assets/2c806e61-33db-4f0e-bec1-126f8bb93773" />


### Step 4: Build the Tableau Dashboard

I imported the cleaned dataset into Tableau and built an interactive dashboard with a top-down executive structure.

The dashboard starts with high-level KPIs, then moves into diagnostic sections covering role risk, demographics, career mobility, salary, training, absence, and satisfaction.

Interactive filters were added for:

* Department
* Job Role
* Gender
* Age Band

The dashboard was designed so users can explore workforce risk across different employee segments.

### Step 5: Build the PowerPoint Insight Story

After building the dashboard, I created a PowerPoint presentation to communicate the key insights and recommended actions.

The PowerPoint deck was not just a screenshot summary. It was structured as a business story:

1. Start with the overall workforce risk
2. Show where attrition is concentrated
3. Explain why demographics and salary need careful interpretation
4. Highlight career mobility and training concerns
5. Connect people experience indicators to retention risk
6. End with clear, actionable HR recommendations

### Step 6: Publish the Dashboard

The final dashboard can be published to Tableau Public so that recruiters, hiring managers, or portfolio viewers can interact with it directly.

After publishing, add the Tableau Public link here:

```markdown
[View the Interactive Dashboard on Tableau Public](Insert Tableau Public link here)
```

---

## 5. Tools and Technologies

| Tool       | Purpose                                          |
| ---------- | ------------------------------------------------ |
| Python     | Exploratory data analysis and data cleaning      |
| Excel      | Data review and checking                         |
| Tableau    | Interactive dashboard development                |
| PowerPoint | Insight presentation and business storytelling   |
| Word       | Written dashboard report                         |
| GitHub     | Project documentation and portfolio presentation |

---

## 6. Dashboard Overview

The dashboard provides one executive view of workforce health.

### Key Metrics

| Metric               |      Value |
| -------------------- | ---------: |
| Total Attritions     |        405 |
| Attrition Rate       |        23% |
| Active Employees     |      1,380 |
| Average Satisfaction | 3.16 / 4.0 |

### Dashboard Sections

| Section                      | Purpose                                         |
| ---------------------------- | ----------------------------------------------- |
| KPI Summary                  | Shows overall workforce health                  |
| Hiring Trend                 | Tracks employee hiring movement over time       |
| Department and Role Analysis | Identifies high-risk workforce areas            |
| Age and Gender Distribution  | Explains workforce composition                  |
| Education Distribution       | Shows workforce qualification profile           |
| Career Heatmap               | Highlights career mobility and progression risk |
| Salary by Gender             | Screens salary distribution patterns            |
| Job Level Distribution       | Shows seniority structure                       |
| Training Sessions            | Measures learning participation                 |
| Absence Days                 | Tracks working condition signals                |
| Satisfaction Scorecard       | Shows employee experience distribution          |

---

## 7. Dashboard Preview

<img width="1605" height="952" alt="HR_Dashboard" src="https://github.com/user-attachments/assets/9e35ff1a-60fd-4611-89ee-f288ff3a641b" />




Recommended folder structure:

```text
images/
└── hr_people_analytics_dashboard.png
```

---

## 8. Key Insights

### Insight 1: Attrition risk is material and role-specific

The dashboard shows 405 total attritions and a 23% attrition rate. This indicates that attrition is a material workforce issue, not a minor HR statistic.

Role-level analysis shows that attrition is uneven across job roles. Some roles, such as Solutions Architect and Sales Representative, show higher risk than others. This means the organisation should not rely only on broad retention programs. Role-specific retention actions are needed.

### Insight 2: Workforce composition affects how HR metrics should be interpreted

The workforce has a strong gender imbalance, with approximately 78% male employees and 22% female employees. This does not automatically prove inequity, but it changes how salary, job level, promotion, and satisfaction data should be interpreted.

A responsible data analyst should avoid making strong equity claims from descriptive charts alone. Instead, the dashboard highlights where deeper controlled analysis is required.

### Insight 3: Career mobility should be monitored as a retention driver

The career heatmap combines years at company, years in current role, years since last promotion, and years with current manager.

This helps identify whether employees may be staying in the organisation but not progressing. Career stagnation can become a retention risk when long-tenured employees do not see clear movement or promotion pathways.

### Insight 4: Salary distribution requires controlled pay equity analysis

The salary charts compare salary bands by gender, while the job level chart provides seniority context.

These visuals are useful as a screening tool, but they are not enough to prove pay equity or inequity. A deeper analysis should control for role, job level, tenure, department, and performance.

### Insight 5: Training participation is strong, but outcome impact is unclear

The dashboard shows strong training participation, especially among employees with multiple training sessions.

However, high training volume does not automatically mean better capability, promotion, or retention. The next analytical step would be to test whether training participation leads to improved promotion outcomes, satisfaction, or lower attrition.

### Insight 6: People experience is moderate-to-positive, not uniformly strong

The satisfaction scorecard shows that many people experience indicators cluster around middle-to-positive scores.

This suggests that employee experience is not poor overall, but it is also not consistently excellent. Job satisfaction, wellbeing, and work-life balance should be monitored with attrition and absence as early-warning indicators.

---

## 9. Recommended Actions
<img width="2117" height="1199" alt="image" src="https://github.com/user-attachments/assets/32e33d05-2ff3-465f-b9fe-c8deebff586d" />

### 1. Implement role-specific retention plans

High-risk roles should be reviewed first. Recommended actions include:

* Exit interview analysis
* Workload review
* Salary benchmarking
* Promotion pathway review
* Manager stay conversations
* Targeted retention planning

### 2. Run a controlled pay equity audit

Salary patterns should be analysed using a controlled method. The analysis should compare salary by gender while controlling for:

* Job role
* Job level
* Department
* Tenure
* Performance rating
* Experience

### 3. Connect training to career progression

Training should be linked to measurable outcomes, not only participation counts.

Recommended follow-up analysis:

* Training sessions vs promotion movement
* Training sessions vs satisfaction score
* Training sessions vs attrition risk
* Training sessions vs job level movement

### 4. Launch a quarterly people experience review

HR leaders should review people experience indicators every quarter alongside attrition and absence patterns.

This can help identify early warning signals before workforce issues become more serious.

---

## 10. PowerPoint Insight Story

The PowerPoint deck was created to present the dashboard findings in a business-friendly way.

### Slide Structure

| Slide   | Story Purpose                                                             |
| ------- | ------------------------------------------------------------------------- |
| Slide 1 | Introduces the HR People Analytics Dashboard and key workforce KPIs       |
| Slide 2 | Shows that attrition risk is material and role-specific                   |
| Slide 3 | Explains how gender imbalance affects interpretation of equity indicators |
| Slide 4 | Highlights career mobility as a retention driver                          |
| Slide 5 | Shows why salary distribution requires controlled pay equity analysis     |
| Slide 6 | Explains why training participation needs outcome testing                 |
| Slide 7 | Shows that people experience is moderate-to-positive, not uniformly high  |
| Slide 8 | Summarises recommended actions for HR leaders                             |



Recommended folder structure:

```text
images/
├── hr_people_analytics_dashboard.png
├── slide_1_dashboard_overview.png
├── slide_2_attrition_risk.png
├── slide_3_workforce_composition.png
├── slide_4_career_mobility.png
├── slide_5_pay_equity.png
├── slide_6_training_absence.png
├── slide_7_people_experience.png
└── slide_8_recommendations.png
```

---

## 11. Repository Structure

```text
HR-People-Analytics-Dashboard/
├── data/
│   ├── raw/
│   │   └── original_hr_dataset.csv
│   └── cleaned/
│       └── cleaned_hr_dataset.csv
├── images/
│   ├── hr_people_analytics_dashboard.png
│   ├── slide_1_dashboard_overview.png
│   ├── slide_2_attrition_risk.png
│   ├── slide_3_workforce_composition.png
│   ├── slide_4_career_mobility.png
│   ├── slide_5_pay_equity.png
│   ├── slide_6_training_absence.png
│   ├── slide_7_people_experience.png
│   └── slide_8_recommendations.png
├── outputs/
│   └── exported_dashboard_files/
├── HR_EDA.ipynb
├── HR_Dashboard.twbx
├── HR_People_Analytics_Dashboard_Report.docx
├── HR_People_Analytics_Deck.pptx
└── README.md
```

---

## 12. Business Value

This project demonstrates how a data analyst can move from raw HR data to business action.

The value of the project is not only the dashboard design, but the full analytical process:

1. Understand the HR business problem
2. Explore the data using Python
3. Clean and prepare the dataset
4. Build an interactive Tableau dashboard
5. Identify meaningful workforce insights
6. Present findings through PowerPoint storytelling
7. Recommend practical actions for business leaders
8. Publish the dashboard for portfolio and stakeholder access

The project demonstrates skills in:

* Data cleaning
* Exploratory data analysis
* HR analytics
* KPI dashboarding
* Tableau visualisation
* Business storytelling
* Insight communication
* Workforce risk analysis
* Evidence-based recommendations

---

## 13. Project Outcome

The final output is an interactive Tableau dashboard supported by a written report and a PowerPoint insight presentation.

The dashboard helps HR leaders monitor workforce risk, identify priority employee groups, and make more informed decisions around retention, career mobility, pay equity review, training effectiveness, and employee experience.

---

## 14. Author

Khoa Nguyen
Master of Business Information Technology
RMIT University
::: 

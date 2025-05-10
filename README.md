# HR Analytics Dashboard (Interactive Power BI Dashboard for HR Insights)

## Project Objective

The goal of this project is to design an interactive and comprehensive HR Analytics Dashboard to help HR teams, executives, and stakeholders monitor, analyze, and improve employee performance, engagement, recruitment efficiency, diversity, and retention across the organization. The dashboard enables data-driven decisions by visualizing critical HR metrics and trends.

## Dataset Used
- <a href="https://github.com/suriya2318/HR-Analytics-Dashboard/blob/main/employee_data.csv"> Employee Information Dataset</a>

- <a href="https://github.com/suriya2318/HR-Analytics-Dashboard/blob/main/employee_engagement_survey_data.csv"> Performance and Engagement Records</a>

- <a href="https://github.com/suriya2318/HR-Analytics-Dashboard/blob/main/training_and_development_data.csv"> Training & Development Data </a>

- <a href="https://github.com/suriya2318/HR-Analytics-Dashboard/blob/main/recruitment_data.csv"> Recruitment Data </a>

## Key Business Questions (KPIs)
•	What is the current employee headcount by department and demographics?

•	How has employee engagement and satisfaction changed over time?

•	Which departments have the highest exit rates and how do they compare to industry benchmarks?

•	Who are the top-performing employees across departments?

•	Is there a correlation between training investment and performance?

•	What is the diversity breakdown (gender, race) across departments and applicants?

•	How efficient is the recruitment pipeline from applicants to hires?

•	Which departments are underperforming or have engagement issues?

•	What are the recommendations based on current HR analytics?

•	HR Dashboard Interaction - <a href="https://github.com/suriya2318/HR-Analytics-Dashboard/blob/main/HR%20dashboard%20Analytics.mp4"> View Dashboard </a>

## Process
1. Data Cleaning & Preparation
   
   •	Verified all datasets for missing values and outliers.
   
   •	Ensured consistent formats (e.g., date formats, categorical labels).
   
   •	Merged and joined tables based on common fields such as EmpID, Department, and StartDate.


2. Data Modeling in Power BI
   
   •	Established relationships between multiple tables (one-to-many, many-to-one).

   •	Created calculated columns and DAX measures for KPIs like Exit Rate, Avg. Performance Score, ROI, etc.

3. Visualization & Dashboard Design

   •	Built six structured dashboards, each focusing on a specific HR domain (e.g., Company Overview, Training, Recruitment).

   •	Used slicers and filters to allow dynamic interaction and drill-down by department, gender, time period, etc.

   •	Applied best practices in design: minimal colors, clear labeling, and meaningful chart types.


## Dashboards Overview

1. Dashboard 1: Company Overview

   •	Total Employees (Card): Displays the total number of current employees.

   •	Active vs. Exited Employees (Pie Chart): Shows the proportion of employees who are currently active versus those who have left.

   •	Department-wise Headcount (Clustered Bar Chart): Compares employee count across departments.

   •	Gender and Race Distribution (Donut Charts): Highlights workforce diversity by gender and race.

   •	EmpID by Start Date & Department Type (Line Chart): Tracks hiring trends over time across different department types.

      ![Company Overview Dashboard](https://github.com/user-attachments/assets/b0bf8e14-beb5-4668-99a2-8d5af969c57f)
   

3. Dashboard 2: Employee Performance & Engagement

   •	Performance Score by Department (Stacked Bar Chart): Shows how performance ratings vary across departments.

   •	Engagement & Satisfaction Score Over Time (Line Chart): Visualizes changes in employee sentiment over time.

   •	Work-Life Balance Distribution (Clustered Column Bar Chart): Shows how employees rate their work-life balance.

   •	Top 10 Performers (Interactive Table): Lists the highest-performing employees with filtering options.

      ![Employee Performance   Engagement Setup Dashboard](https://github.com/user-attachments/assets/c6cc292a-1793-4c8b-9362-e76ff831d432)


5. Dashboard 3: Training & Development

   •	Number of Trainings Conducted (Card): Displays the total training sessions delivered.

   •	Average Training Cost by Department (Bar Chart): Compares training spend across departments.

    •	Training Outcome vs. Performance Score (Correlation Bar Chart): Analyzes if training leads to better performance.

   •	Training Hours per Employee (Clustered Bar Chart): Shows how much training each department's employees receive.

      ![Training   Development Dashboard](https://github.com/user-attachments/assets/a7361dcf-9a71-479e-ae76-7034323008a1)


7.  Dashboard 4: Recruitment Analysis
   
      •	Total Applicants vs. Hired (Funnel Chart): Visualizes the hiring funnel from applicants to final hires.
   
      •	Experience Level by Applicants (Bar Chart): Shows the distribution of experience levels among applicants.
      
      •	Desired Salary Distribution (Histogram): Highlights the salary expectations of job applicants.
      
      •	Gender/Diversity Stats among Applicants (Donut Chart): Shows the diversity breakdown of applicants.

      ![Recuiremnet Analysis Dashboard](https://github.com/user-attachments/assets/47c2503d-bc1b-4693-ab30-de767fdb578a)

9. Dashboard 5: Problem Identification
   
     •	Count of Employees Over Time (Line Chart): Highlights workforce growth trends by department from 2018 to 2023, revealing staffing imbalances.
     
     •	Problem Area Detected (Card): Quickly shows the total number of HR red flags (e.g., attrition, skill gaps, imbalance).
     
     •	Diversity by Department (Matrix): Highlights gender gaps in departments, flagging areas lacking inclusion.
     
     •	Department Headcount vs. Performance (Stacked Bar Chart): Compares employee count with department performance, showing underutilization or overstaffing.
     
     •	Declining Engagement Over Time (Line Chart): Tracks employee engagement decline, signaling low morale or dissatisfaction risks.

    ![Problem Indentification Dashboard](https://github.com/user-attachments/assets/d113fd84-c191-43d9-ad55-96d66c098dc8)

11. Dashboard 6: Solutions & Recommendations
   
     •	Current Headcount per Department (Clustered Column Chart): Displays the current team size vs. optimal staffing to guide hiring decisions.
   
     •	Exit Rate vs. Benchmark (Line & Clustered Column Chart): Compares attrition rates with company standards to monitor turnover risks.
     
     •	Quarterly Engagement & Satisfaction Trend (Line Chart): Shows engagement drop across quarters, prompting immediate employee wellness actions.
     
     •	Smart Training Investment vs. Performance ROI (Scatter Plot): Identifies which training programs deliver real performance gains, helping optimize L&D spend.


      ![Solution   Recommendations Dashboard](https://github.com/user-attachments/assets/d8c77633-ebe9-4eef-b1ea-dca1da81341f)

    
## Project Insights
   •	Departments with high exit rates also show declining engagement.
   
   •	A direct positive correlation exists between targeted training investments and performance ROI.
   
   •	Gender and racial diversity is uneven across departments, indicating areas for DEI improvement.
   
   •	Top performers are often linked to departments with higher training engagement.
   
   •	Applicant diversity data reveals potential recruitment bias or sourcing gaps.
   
   •	Certain departments are struggling with satisfaction, especially where exit rates are higher than benchmarked norms.
   

## Final Conclusion

This HR Analytics Dashboard provides actionable insights into workforce trends and issues, enabling data-driven strategies for improving employee retention, diversity, engagement, and performance. By investing strategically in training and addressing problem departments, the organization can boost productivity and employee satisfaction. Additionally, targeted recruitment strategies can enhance diversity and hiring efficiency.




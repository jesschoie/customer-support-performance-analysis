# customer-support-performance-analysis
**Project Overview**

This project analyses customer support ticket data to evaluate service desk performance and customer satisfaction. The analysis focuses on identifying trends in ticket volumes, resolution times, agent workload, and customer feedback. SQL was used to extract and analyse key metrics, and the results were visualised in a dashboard.

**Dataset Description**

The Kaggle dataset contains support ticket records including issue categories, priority levels, resolution times, assigned agents, and customer satisfaction scores.

Key fields include:

•	Ticket_ID

•	Issue_Category

•	Priority_Level

•	Ticket_Channel

•	Submission_Date

•	Resolution_Time_Hours

•	Assigned_Agent

•	Satisfaction_Score

**Analysis Questions**

•	What are the trends in ticket volume over time?

•	Which issue categories generate the most tickets?

•	Does resolution time impact customer satisfaction?

•	How does resolution time vary by priority level?

•	How is workload distributed across support agents?

**SQL Analysis**

SQL queries were used to calculate key performance metrics including ticket volumes, average resolution times, and satisfaction scores. Aggregation functions and grouping were used to analyse trends across issue categories, priority levels, and support agents.

**Dashboard**

A dashboard was created in Tableau to visualise key service desk performance metrics, including ticket trends, resolution times, and agent performance.

<img width="940" height="629" alt="image" src="https://github.com/user-attachments/assets/6a748a7f-8f2e-4cbe-8664-a465da0ad835" />

View the interactive Dashboard in Tableau: https://public.tableau.com/app/profile/jess.choie/viz/CustomerSupportPerformanceDashboard_17738410119610/CustomerSupportPerformanceDashboard

**Key Insights & Recommendations**

•	Critical and high priority tickets are resolved faster than lower priority tickets, indicating that the prioritization system is functioning effectively and urgent issues are handled promptly.

•	No clear correlation shown between ticket resolution time and customer satisfaction, suggesting other factors may influence customer experience. 

•	Billing and Fraud issues consistently receive lower satisfaction scores, indicating that issue type plays a more significant role in customer satisfaction. Billing and Fraud handling processes should be reviewed and additional training provided for agents handling these types of issues. 

•	Technical issues generate the highest number of support tickets, signifying they are the most common source of customer problems and a major driver in workload. Further investigation needs to be done into recurring technical issues to identify root causes. 

•	Although there are less Fraud tickets, they are disproportionately classified as critical or high priority. Sufficient resources and clear escalation paths should be in place for fraud-related incidents to maintain fast response times and minimise potential business impact. 

•	Ticket volume tends to decline towards the end of the week but increases again on Sunday, which indicates a cyclical pattern in support demand. Staffing levels should be adjusted to align with demand patterns, to ensure higher coverage during the busier periods. 

•	Anya Sharma works on the most tickets and has the longest average resolution time. Further investigation is needed to determine whether this is due to workload imbalance or ticket complexity, and redistribution of tickets or additional training may be required. 

**Tools Used**

•	MySQL

•	Tableau	 

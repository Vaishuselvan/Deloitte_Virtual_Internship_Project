📊 Data Analytics – Deloitte Virtual Internship 
(Daikibo Project)

This project is part of the Virtual Internship Program by Deloitte Australia, where we analyze and visualize industrial and workforce data from Daikibo's factories using Tableau and Excel. The analysis is divided into two core tasks:

✅ Task 1: Machine Health Dashboard using Tableau
Objective:
To analyze telemetry data collected from Daikibo's four global factory locations and determine:

Which location experienced the most machine breakdowns.

What types of machines broke down most frequently in that location.

Factory Locations:
Meiyo Factory – Tokyo, Japan

Seiko Factory – Osaka, Japan

Berlin Factory – Berlin, Germany

Shenzhen Factory – Shenzhen, China

Each factory has 9 machine types, sending health status messages every 10 minutes.

📈 Steps:
Converted raw JSON telemetry data into tabular format.

Created a calculated field Unhealthy to assign 10 minutes of potential downtime for every "Unhealthy" status.

Built a Tableau dashboard with:

Bar Chart 1: Down Time per Factory

Bar Chart 2: Down Time per Device Type

Set up a dashboard filter: Selecting a factory filters device-level data accordingly.

Interacted with the dashboard to find the most affected location and machines.

🌐 Dashboard Link: https://public.tableau.com/app/profile/jaya.vaishnavi.devi.s/viz/Daikibo_17519070103220/Dashboard1?publish=yes

✅ Task 2: Equality Classification in Excel
Objective:
To help the client evaluate gender pay equality across different factories and job roles by classifying equality scores into categories.

Dataset:
Factory: Name of the factory

Job Role: Role of the employee

Equality Score: Ranges from -100 to +100, where 0 is considered ideal

📈 Steps:
Added a new column: Equality Class

Applied logic based on the score to categorize the records:

Fair: Score is between -10 and +10

Unfair: Score is between -20 and -11 or +11 and +20

Highly Discriminative: Score is less than -20 or greater than +20

🚀 Tools Used:
Tableau Public – Data visualization & dashboard

Microsoft Excel – Data transformation & formula-based classification

🧠 Outcome:
Identified factory and machine types with the most downtime.

Built a dynamic Tableau dashboard for operational insights.

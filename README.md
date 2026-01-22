Student Productivity & Burnout Risk Analysis using Power BI
Project Summary

In recent years, students face increasing academic pressure, leading to reduced productivity and a higher risk of burnout. Traditional academic performance tracking focuses mainly on grades and attendance, often ignoring behavioral and wellbeing factors. This project aims to bridge that gap by analyzing student study behavior and wellbeing data to identify productivity patterns and predict burnout risk using data analytics.

The Student Productivity & Burnout Risk Dashboard is developed using Microsoft Power BI. The project analyzes how factors such as study duration, focus level, sleep hours, stress levels, distractions, and breaks impact student productivity and burnout.

Objectives

To analyze students’ daily study behavior and wellbeing patterns

To measure productivity using calculated performance metrics

To design a custom Burnout Risk Score using multiple influencing factors

To identify students at high risk of burnout

To provide actionable insights for early intervention

Data Description

The project uses three structured datasets:

StudentMaster – Contains basic student information such as Student ID, year of study, and academic stream.

StudySessions – Records daily study activities including subject, study duration, focus level, distractions, start time, and breaks taken.

Wellbeing – Captures health-related factors such as sleep hours, stress level, mood, and energy level.

All tables are connected using StudentID in a star schema model to ensure accurate filtering and analysis.

Methodology

Data was cleaned and transformed using Power Query, where incorrect data types were fixed and derived fields such as Time of Day were created. Relationships were established in the data model to enable cross-table analysis.

Key performance indicators were created using DAX measures, including:

Total Study Hours

Average Focus Level

Average Sleep Hours

Productivity Score

Burnout Risk Score

The Burnout Risk Score was calculated using weighted factors such as study hours, sleep deficit, stress level, and lack of focus. Based on this score, students were classified into Low Risk, Medium Risk, or High Risk categories.

Dashboard Design

The dashboard consists of three interactive pages:

Overview – Displays high-level KPIs, study trends, and burnout distribution.

Behavior Patterns – Analyzes focus by time of day, distraction types, burnout by subject, and the relationship between breaks and productivity.

Burnout Monitor – Highlights at-risk students using conditional formatting, student-wise burnout scores, and sleep vs burnout analysis.

Slicers and navigation buttons allow users to interactively explore the data.

Key Insights

Morning study sessions show the highest focus levels

Subjects like Java and Python demonstrate higher burnout risk

Lower sleep duration strongly correlates with increased burnout

Excessive breaks negatively impact productivity

Conclusion

This project demonstrates the effective use of Power BI for behavioral and wellbeing analytics. By introducing a custom burnout scoring system, the dashboard moves beyond descriptive reporting to provide meaningful insights and early warning indicators. The solution can be used by educational institutions or mentors to monitor student wellbeing, improve productivity, and prevent burnout through timely intervention.

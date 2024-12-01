# **Career Track Analysis Project**

This repository contains the **Career Track Analysis Project**, a comprehensive analysis of career track enrollments, completions, and trends. The project uses SQL and Tableau for data exploration, visualization, and insights.

---

## **Project Overview**
The Career Track Analysis Project provides insights into the following:
1. **Enrollment Trends**: Monthly enrollments in different career tracks.
2. **Completion Rates**: The fraction of students completing their tracks over time.
3. **Duration for Completion**: Distribution of time taken by students to complete their tracks.

## **Goal**
The results aim to assist in understanding student behavior towards career track completion and optimizing these career track programs to boost engagement and completion rates.

## **Tools Used**
**SQL, Tableau**

## **Key Visualizations**
### 1. **Enrollments by Track**
   - Displays the total enrollments for each career track (Business Analyst, Data Analyst, Data Scientist).

### 2. **Number of Enrollments and Fraction of Completions**
   - A combination of bar and line charts showing:
     - The monthly number of enrollments.
     - The completion fraction for enrolled students.

### 3. **Duration for Track Completion**
   - A bar chart illustrating the distribution of completion times:
     - Same day, 1 to 7 days, 8 to 30 days, 31 to 60 days, 61 to 90 days, 91 to 365 days, and 366+ days.

---

## **Insights from Analysis**

- The Data Analyst track has the highest number of enrollments, followed by Data Scientist and Business Analyst tracks.
  
- Completion rates fluctuate over time, with the highest rates observed mid-year and a significant drop in September.
Duration Insights:

- Most students complete their tracks in 91 to 365 days. A smaller fraction of students complete tracks in under 60 days, indicating room for improvement in pacing and engagement.

## **Recommendations**

- Introduce quarterly subscription plans tailored to the average completion time of 91–365 days.
- Encourage consistent learning by offering incentives for maintaining weekly or monthly learning streaks.
- Focus on engagement strategies during low-completion periods (e.g., September).

 ---

## **Repository Structure**
```plaintext
Career Track Analysis Project/
│
├── Dashboard and Interpretation.md        # Link to google docs containing dashboard and interpretation.
├── EERD of Career Track Analysis Project.pdf # Enhanced Entity-Relationship Diagram for the database schema.
├── career_track_completions.csv             # Processed dataset containing enrollment and completion details.
├── queries.sql                              # SQL queries used for data extraction and transformation.
├── sql_and_tableau.sql                      # SQL queries used specifically for Tableau integration.
└── README.md                                # Project documentation (this file).

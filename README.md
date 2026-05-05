# Student Performance Analysis

📌 **Purpose of the Project**

This project analyzes high school student performance data from two schools in Portugal to identify factors that most affect grades and attendance. The main objectives are:

* To determine what factors have the biggest effect on student grade performance.
* To identify key differences in attendance between the top and bottom 25th percentile students.
* To provide recommendations for how education decision-makers can allocate budgets to improve student outcomes.

---

🔍 **Analysis Performed**

1. Data Cleaning & Preparation (649 rows, 10 columns)
2. Multiple Regression Analysis on student grades
3. Residual Plot Analysis to validate model fit
4. Correlation Analysis across all variables
5. Quartile Analysis on attendance patterns

---

📌 **Results**

* Prior failures had the strongest negative correlation with grades — students who failed at least once rarely achieved top scores, and scores declined further with each additional failure.
* School support (tutoring and in-school programs) had a significant positive impact on grades.
* Longer travel time negatively affected student performance.
* The residual plots showed no strong patterns, indicating the regression model fits the data reasonably well.

---

📌 **Recommendations**

* Allocate extra resources for students who fail in the first quarter to help them recover in the second quarter.
* Invest in in-school tutoring and support programs for struggling students.
* Partner with local transportation agencies or provide school buses to reduce the negative impact of long commutes.
* Offer a flexible hybrid learning model for students with commute times of four or more hours.

---

📌 **Data Source**

Student Performance Dataset via UCI Machine Learning Repository:
https://archive.ics.uci.edu/dataset/320/student+performance

---

📌 **Technologies Used**

* Microsoft Excel (Regression, Correlation, Data Visualization)
* Git & GitHub

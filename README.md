# Customer-Engagement-Analysis-in-Excel


## 🏆 Customer Engagement Analysis in Excel Project  

### 📌 Introduction  
The 365 Company embarked on an ambitious journey in 2022, introducing numerous new features to its website platform aimed at fostering student engagement and driving company growth. Among these enhancements were an XP system, in-app coins, leaderboards, and streaks, designed to motivate and reward students for consistent learning habits. Additionally, an expanded course library broadened the scope of available topics.  

This project is a **Customer Engagement Analysis in Excel**, investigating the impact of these new platform features on student engagement. The dataset provided by the 365 Company is analyzed to draw meaningful insights into user behavior, providing a realistic and relevant context for the analysis.  



### ❓ Problem Statement  
The central question addressed in this project is:  
**Did the new website features boost student engagement in Q4 2022 compared to Q4 2021?**  

To analyze this, various data analysis techniques, statistical tests, and Excel functions were employed.  

#### 🏗 Tasks Overview:  
✔️ **Task 1:** Analyzing engagement levels of low-engagement users in Q4 2021 and Q4 2022.  
✔️ **Task 2:** Calculating skewness and kurtosis to assess engagement distribution.  
✔️ **Task 3:** Determining confidence intervals for different student groups.  
✔️ **Task 4:** Conducting hypothesis testing on the impact of platform features.  
✔️ **Task 5:** Investigating engagement differences between US and Indian free-plan students.  



## 📊 Task 1: Low-Engagement User Analysis  

The `Task 1 and 2` sheet contains users who watched between 1 and 100 minutes in 2021, divided into **Paid** and **Free** plan users. Low-engagement users represent the most significant potential for growth, and increasing their engagement could have a major impact on platform usage.  

### 🔎 Analysis for Paid Plan Users  
- **Mean:** Increased from **33.80 min (Q4 2021)** to **273.02 min (Q4 2022)** 🚀  
- **Median:** Increased from **26.33 min** to **40.28 min**  
- **Standard Deviation:** Increased from **28.21 min** to **854.58 min**  

**📌 Key Takeaway:**  
Paid-plan students who had low engagement in 2021 significantly increased their engagement in 2022. However, the **higher standard deviation** suggests a wide variation in engagement levels.  



### 🔎 Analysis for Free Plan Users  
- **Mean:** Increased from **25.39 min (Q4 2021)** to **117.64 min (Q4 2022)**  
- **Median:** **Dropped** from **14.17 min** to **11.83 min**  
- **Standard Deviation:** Increased from **26.23 min** to **468.93 min**  

**📌 Key Takeaway:**  
Despite an increase in the **average** engagement, the **typical student (median)** actually watched **less** content. This suggests that a **small group of users** heavily influenced the mean, while most students did not increase their engagement significantly.  



## 📈 Task 2: Skewness and Kurtosis Analysis  

**Skewness** measures asymmetry in the distribution.  
**Kurtosis** measures the "peakedness" of the distribution.  

### 📊 Analysis for Paid Plan Users  
- **Skewness:** Increased from **0.63 (Q4 2021)** to **7.07 (Q4 2022)**  
- **Kurtosis:** Increased from **-0.85** to **58.48**  

### 📊 Analysis for Free Plan Users  
- **Skewness:** Increased from **1.17 (Q4 2021)** to **15.06 (Q4 2022)**  
- **Kurtosis:** Increased from **0.36** to **315.76**  

**📌 Key Takeaway:**  
Both **skewness and kurtosis increased**, indicating that a **small group of students** contributed to a disproportionately large amount of engagement.  



## 🎯 Task 3: Confidence Intervals  

Confidence intervals provide a range of values where we expect the **true population mean** to lie.  

### 🔍 Confidence Intervals for Paid Plan Users  
- **Q4 2021:** [316.25, 348.76]  
- **Q4 2022:** [351.99, 384.72]  
- **Interpretation:** Since the confidence intervals **do not overlap**, the increase in engagement is statistically significant.  

### 🔍 Confidence Intervals for Free Plan Users  
(TBD – Add analysis results)  



## 🧪 Task 4: Hypothesis Testing  
In this task, hypothesis testing was conducted to analyze customer engagement metrics between different periods and subscription plans. A two-sample f-test was used to examine the variances for free- and paid-plan subscribers' engagement levels.
Key highlights:

Null Hypothesis for Paid Plan Users: Engagement in Q4 2021 is higher than or equal to Q4 2022 for paid-plan users.
Result: Statistical evidence to reject the null hypothesis, showing a significant increase in engagement in Q4 2022 for paid-plan users.
Null Hypothesis for Free Plan Users: Engagement in Q4 2021 is higher than or equal to Q4 2022 for free-plan users.
Result: No significant change in engagement for free-plan users.
This task highlights the importance of engagement differences between free and paid plans and the significance of considering Type I and Type II errors when drawing conclusions.



## 🌎 Task 5: Engagement in the US vs. India  
**(Coming Soon)**  



## 🛠 Tools & Techniques Used  
📌 **Excel**: Data cleaning, analysis, statistical calculations  
📌 **Descriptive Statistics**: Mean, Median, Standard Deviation  
📌 **Inferential Statistics**: Confidence Intervals, Hypothesis Testing  
📌 **Visualization**: Charts and tables in Excel  



## 📜 Conclusion  
The analysis shows that paid-plan students had a substantial increase in engagement, while free-plan students had mixed results. Further analysis is needed to understand how to **improve engagement for free users** and **enhance overall platform effectiveness**.  

## Detailed Report
For a comprehensive breakdown of the analysis, including methodology, transformations, and insights, refer to [Project_Report.pdf](./Project_Report.pdf).


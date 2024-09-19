# Omnipresent_telecommunication-project-

### Introduction

This project analyzes customer service performance data to provide actionable insights for enhancing operational efficiency and improving customer satisfaction. The data, gathered between January and March 2021, includes metrics such as call handling efficiency, agent performance, customer sentiment, and call abandonment rates. By examining these areas, this project aims to identify key areas for improvement and recommend strategies that align with best practices in customer service management.

The analysis was conducted using tools like Power BI to visualize trends and pinpoint areas where the team can optimize resources, enhance customer experiences, and ensure better agent productivity. This report serves as a demonstration of my skills in data analysis, visualization, and strategic recommendations within a customer service context.

### **Data Cleaning and Processing**
I removed columns by eliminating irrelevant or redundant ones to reduce the dataset size and focus on only the necessary data. I replaced null values by addressing missing data with appropriate values, such as the mean, median, or a default value, to ensure consistency and avoid errors in analysis. I also cleaned up textual data by removing unwanted characters or symbols to maintain accuracy in string-based fields, such as removing special characters and extra spaces.
Next, I standardized the data by converting it into a consistent format, ensuring uniformity in elements like date formats, capitalization, and currency units. Finally, I split the data into fact and dimension tables, organizing it to improve structure and performance for future analysis, with fact tables containing transactional data and dimension tables holding descriptive attributes.


![Screenshot_20240918-233507_Drive](https://github.com/user-attachments/assets/d7969a60-1869-4021-9e88-27debef498ba)

![Screenshot_20240918-233456_Drive](https://github.com/user-attachments/assets/c0d91eab-2f97-4bd5-bf36-660a2a35d196)

### Analysis

- **Overall Customer Satisfaction:** The dataset indicates a high level of customer satisfaction, with responses categorized into six levels: Extremely Satisfied, Very Satisfied, Satisfied, Neutral, Dissatisfied, and Very Dissatisfied. Of note, 843 customers were extremely satisfied, while 417 expressed dissatisfaction.
  
- **Call Handling Efficiency:** Out of 5,000 total calls, 4,054 were answered, while 946 were abandoned, resulting in a **call abandonment rate** of about 19%. The **average speed of answer** was 54.7 seconds, which may need improvement to reduce the number of abandoned calls.

- **Agent Performance:** The agents' average talk durations were relatively consistent, ranging from 2.89 to 3.18 minutes. Jim answered the most calls (536), while Stewart had the least (477). Performance consistency suggests adequate handling times but may signal room for operational efficiency gains.

- **Call Traffic Patterns:** The busiest call periods occurred between 9:00 AM and 5:00 PM, with peak call volume around 11:00 AM and 2:00 PM. This information could be useful for staffing optimizations.

- **Customer Sentiment:** A majority of customers reported high satisfaction, but the dissatisfaction levels (417 dissatisfied) indicate potential areas for improvement in service delivery. This could be tied to issues such as longer waiting times or unsatisfactory resolutions.

- **Call Abandonment:** The 19% call abandonment rate suggests that nearly 1 in 5 customers abandoned calls before receiving assistance. The **average speed of answer (54.7 seconds)** is likely contributing to this rate, meaning that either more staff or more efficient call handling processes could improve customer retention.

- **Agent Productivity:** The difference in call volumes handled by agents is minimal, suggesting an evenly distributed workload. However, individual agent talk times vary slightly, indicating opportunities to analyze specific conversations for insights into why certain agents handle calls more efficiently.

- **Operational Bottlenecks:** The spikes in call volume at specific times suggest the need for better resource allocation. More agents should be scheduled during peak periods, particularly around mid-morning and mid-afternoon.

### Recommendations
1. **Reduce Call Abandonment Rate:** Implement strategies to reduce the 19% abandonment rate by decreasing the average wait time. This could involve:
   - Increasing staffing during peak hours.
   - Exploring automated self-service options for common customer issues.
   
2. **Enhance Agent Performance:** 
   - Conduct training sessions for agents with lower talk durations to ensure quality service is maintained.
   - Review call recordings to identify best practices from high-performing agents that can be shared with the rest of the team.

3. **Optimize Staffing Levels:** Based on the call traffic patterns, more agents should be assigned during peak times (e.g., 11 AM and 2 PM) to ensure that the workload is balanced and wait times are reduced.

4. **Improve Customer Satisfaction:** To lower the dissatisfaction rate, consider gathering specific feedback from dissatisfied customers. This can help identify recurring issues such as long wait times, insufficient resolutions, or agent performance gaps.

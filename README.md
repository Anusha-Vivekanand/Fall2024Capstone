# Fall2024Capstone : Swire Coca-Cola Capstone Project
### **Summary of Business Problem and Project Objective**  
Swire Coca-Cola, a leading global beverage manufacturer, faces substantial challenges due to unexpected equipment failures across its production plants. These unplanned breakdowns reduce operational capacity to 94.4% and lead to an estimated $60 million in annual losses, affecting both efficiency and profitability.

The goal of this project was to address these challenges by utilizing predictive analytics. By examining machine performance data, the project aimed to forecast failures, improve maintenance scheduling, and enhance overall production efficiency.

---

### **Group’s Solution to the Business Problem**  
Our team developed a predictive maintenance strategy by employing survival analysis and regression modeling techniques. This approach enabled us to detect patterns of frequent failures, estimate time-to-failure probabilities, and predict downtime durations. Key elements of our solution included:

- **Survival Analysis**: Kaplan-Meier estimators were used to determine time-to-failure probabilities for critical equipment, such as valves and fillers, across different functional locations.
- **Regression Models**: We evaluated multiple regression models, ultimately identifying ElasticNet as the most effective, achieving a Test RMSE of 82.27.  

The insights generated informed actionable recommendations for optimizing maintenance schedules and inventory management, leading to reduced downtime and improved operational efficiency.

---

### **Business Value of the Solution**  
The predictive maintenance framework created by this project delivers significant value to Swire Coca-Cola by addressing the root causes of unexpected machine breakdowns. The key benefits include:

- **Enhanced Operational Efficiency**: Minimizing unplanned downtime has the potential to improve production uptime by 15-20%, enabling smoother operations.  
- **Cost Reduction**: A 36% reduction in unplanned downtime could significantly cut annual losses and lower repair and labor costs associated with breakdowns.  
- **Inventory Optimization**: Insights into frequently replaced components, such as valves and fillers, allow for better inventory planning, reducing overstocking and ensuring critical parts are readily available.  
- **Strategic Resource Allocation**: The solution enables prioritization of high-risk locations, optimizing the deployment of labor and spare parts to reduce disruptions.  
- **Proactive Maintenance Practices**: Shifting from reactive to proactive maintenance improves reliability and extends the lifespan of equipment.  

---

### **Difficulties Encountered**  
Throughout the project, our team faced several challenges:

1. **Data Gaps**: Up to 70% of the dataset had missing information in key fields, posing a challenge for analysis. We had to carefully balance retaining data integrity while filling gaps.  
2. **Lack of Machine-Specific Data**: Missing details about machine age and usage patterns limited our ability to consider these factors in predictions, which could have enhanced the analysis.  
3. **Time Constraints**: Managing project deliverables while experimenting with various models required efficient coordination and prioritization.
4. **Non Conventional ML model approach**: We were able to experiment with non conventional tests and algorithms apart from regression models

Despite these obstacles, we developed creative solutions to extract valuable insights and deliver impactful results.

---

### **Learning Received**  
This project provided a hands-on opportunity to tackle real-world data challenges and reinforced the value of adaptability and problem-solving. Key lessons included:

- **Survival Analysis Expertise**: Learning and applying Kaplan-Meier estimators for evaluating time-to-failure probabilities was a new and valuable experience.  
- **Dealing with Imperfect Data**: Working with incomplete datasets taught us how to navigate limitations while ensuring the validity of our analysis.  
- **Effective Collaboration**: Teamwork was critical to balancing tasks and leveraging individual strengths to meet objectives.  
- **Business-Driven Analytics**: The importance of aligning analytical findings with actionable business strategies was a recurring theme, emphasizing the role of data in driving decisions.  

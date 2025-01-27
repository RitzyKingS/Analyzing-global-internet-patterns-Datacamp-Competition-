🚀 **Completed the DataCamp Competition: Data Visualization Dashboard for Internet Usage Trends** 🌐📊

🔗 **Explore the Interactive Dashboard**: [View Dashboard](https://lookerstudio.google.com/u/0/reporting/7c0563c6-172a-40ea-b11a-087340488806/page/r75dE)  
![Interactive Dashboard](https://raw.githubusercontent.com/RitzyKingS/Analyzing-global-internet-patterns-Datacamp-Competition-/main/Images/Dashboard-Image.png)

I’m excited to share that I’ve successfully completed the **DataCamp Competition** focused on analyzing and visualizing global internet usage trends from **2000-2023** 🌍💻. As part of the challenge, I built an interactive dashboard that tracks the **Year-over-Year (YoY) Changes**, **Geographical Distribution**, and **Growth Rate** of internet usage across countries. The solution provides meaningful insights into how internet penetration has evolved over time 🌐📈.

### 🔑 **Key Highlights of the Dashboard**:
- **Growth Rate Overview**: Analyzes the global growth of internet usage.
- **Trend Analysis**: Visualizes internet usage trends over time for each country.
- **Geographical Distribution**: Displays internet usage across countries in 2023.
- **Year-over-Year (YoY) Change**: Highlights which countries have shown the largest growth in internet usage.

### 📊 **Code Snippet**:
Here’s a peek at how the code looks for building the visualizations in Python:

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load and preprocess the data
data = pd.read_csv('internet_usage_data.csv')

# Plotting the growth rate
plt.figure(figsize=(10,6))
sns.lineplot(x=data['Year'], y=data['Global Growth Rate'])
plt.title('Global Internet Usage Growth Rate (2000-2023)', fontsize=16)
plt.xlabel('Year', fontsize=12)
plt.ylabel('Growth Rate (%)', fontsize=12)
plt.show()
```

### 📸 **Dashboard Visualizations**:
Here are some visual snapshots from the dashboard that showcase the global internet usage trends:

- ![Internet Usage Trend](https://raw.githubusercontent.com/RitzyKingS/Analyzing-global-internet-patterns-Datacamp-Competition-/main/Images/Dashboard-Image.png)
- ![Interactive Dashboard](https://raw.githubusercontent.com/RitzyKingS/Analyzing-global-internet-patterns-Datacamp-Competition-/main/Images/internet_usage_growth.png)

🔗 **Solution provided via DataCamp challenge**.

I'm thrilled to have had the opportunity to work on this project and further enhance my **data analysis** and **visualization** skills. This experience not only provided me with valuable insights into global internet usage trends, but also deepened my expertise in using **Looker Studio**, **Python**, and other visualization tools to translate complex data into actionable insights.

### 🔍 **Key Takeaways**:
- Hands-on experience with advanced data visualization tools 🛠️
- Insights into the global impact of internet usage across countries 🌍
- Strengthened skills in presenting data in an engaging and informative format 📊
- Developed a deeper understanding of the **Year-over-Year (YoY)** changes in internet penetration

### 💬 **Let’s Connect!**
Feel free to reach out if you're interested in learning more about the project, discussing data visualization techniques, or sharing insights on global internet usage trends. I’m always open to exchanging ideas with fellow data enthusiasts and professionals!

🔗 **Solution provided via DataCamp challenge**.

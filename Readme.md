⚽ FIFA Player Analysis & Team Recommendation
🎯 Problem Statement
A new football club “Brussels United FC” aims to build its team using a data-driven approach. The objective is to analyze FIFA player data and recommend a set of players based on performance, value, and budget constraints.
📄 Reference:

📁 Dataset
	•	Dataset contains information for 18,000+ football players
	•	Includes:
	◦	Age
	◦	Overall rating
	◦	Player value
	◦	Wage
	◦	Physical attributes
	◦	Club and contract details

🛠️ Tools & Technologies
	•	Python
	•	Pandas, NumPy
	•	Matplotlib, Seaborn
	•	Jupyter Notebook

🔍 Approach
1. Data Preprocessing
	•	Converted columns like Value, Wage, Release Clause to numeric format
	•	Cleaned and formatted:
	◦	Height, Weight
	◦	Contract dates
	•	Handled missing values using mean imputation

2. Exploratory Data Analysis (EDA)
	•	Distribution analysis of Overall player ratings
	•	Pair plots for:
	◦	Overall, Value, Wage
	◦	Height, Weight
	◦	Reputation
	•	Identified relationships between player attributes

3. Player Selection Analysis
	•	Identified Top 20 players based on Overall rating and contract expiry
	•	Analyzed:
	◦	Average wage
	◦	Average age
	◦	Correlation between performance and value

📈 Key Insights
	•	Overall player ratings range between 61–94
	•	Strong correlation between Overall rating and player value (≈ 0.79)
	•	High-performing players tend to have higher market value and wages
	•	Identified top players suitable for team selection within constraints

📎 Project Files
	•	📓 Notebook: notebooks/NPV_mini_project.ipynb
	•	📊 Presentation: presentation/NPV presentation.pptx
	•	📂 Dataset: data/fifa.csv

🚀 Conclusion
This project demonstrates:
	•	Data cleaning and preprocessing skills
	•	Exploratory data analysis techniques
	•	Ability to derive insights for real-world decision making

🔮 Future Improvements
	•	Apply machine learning models for player recommendation
	•	Build an automated selection system
	•	Include budget optimization strategies

📌 Key Skills Demonstrated
	•	Data Cleaning
	•	Exploratory Data Analysis (EDA)
	•	Data Visualization
	•	Business Insight Generation

⭐ If you find this project useful, feel free to explore and connect!

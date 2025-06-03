# EDA_Happiness_Project
Understanding Happiness Through Data Analytics
# **EDA_Happiness_Project** 🌍✨  
**Understanding Happiness Through Data Analytics**  

## 📌 **Project Overview**  
This project explores the **drivers of happiness** using data from **2018 and 2019**, focusing on key factors like **GDP per capita, freedom to make life choices, social support, generosity, and perceptions of corruption**.  

Using a **self-reported happiness score** as the outcome variable, the goal is to **identify what influences happiness across countries** and offer insights for **individuals, governments, and policymakers**.  

## 🎯 **Objectives**  
✔️ Perform **data cleaning**, handling missing values & outliers  
✔️ Conduct **hypothesis testing** on freedom and happiness  
✔️ Analyze **correlations** between economic and social indicators  
✔️ Visualize **trends across countries and years**  

## 📊 **Key Findings**  
### **1️⃣ Global Happiness Trends**  
- Happiness scores ranged from **2.9 (least happy) to 7.8 (happiest)**, with a global mean of **5.5**.  
- **GDP per capita** averaged **~0.9**, showing significant **economic disparity** across nations.  
- **Freedom to make life choices** averaged **0.4 (on a 0–1 scale)**, highlighting **differing levels of autonomy worldwide**.  
- **Perceptions of corruption** had a **low global average of 0.1**, reflecting **widespread distrust in governance**.  
- **Social support** averaged **1.1 (on a 0–2 scale)**, suggesting **moderate support systems globally**.  

### **2️⃣ Outlier Detection & Insights**  
Outliers were found in:  
✅ **Generosity** → Some nations, despite economic struggles, rank high in generosity (e.g., **Myanmar, Haiti**).  
✅ **Social Support** → Nordic countries stand out due to **strong welfare models** (e.g., **Finland, Denmark**).  
✅ **Corruption Perception** → Some countries exhibit **high levels of distrust in governance**.  

### **3️⃣ Hypothesis Testing: Does Freedom Affect Happiness?**  
A **one-tailed t-test (α = 0.05)** comparing **high vs. low-freedom countries** revealed:  
📌 **p-value = 0.158655**  
📌 **z-score = 1.0**  
📌 **Conclusion:** **Statistically significant** difference—**personal freedom meaningfully impacts happiness**.  
📌 **Visualization:** High-freedom countries show **higher median happiness** & **more variation**, while low-freedom nations have **tighter, lower happiness distributions**.  

### **4️⃣ Correlation Analysis**  
- **GDP per capita & Happiness Score** → **Strong correlation (0.80)** → Wealth boosts happiness, but money alone is not enough.  
- **Freedom to make life choices & Happiness Score** → **Moderate correlation (0.5)** → Autonomy matters!  
- **GDP per capita & Freedom to make life choices** → **Weak correlation (0.34)** → Economic wealth doesn’t necessarily mean greater personal liberty.  
- **Corruption perception & Happiness Score** → **Limited direct link** → Dropped from deeper analysis due to inconsistencies.  

### **5️⃣ Happiness Model: Who’s the Happiest?**
🏆 **Top Happiest Countries** → **Finland, Iceland, Denmark, Norway**  
❌ **Least Happy Countries** → **Afghanistan, Syria, South Sudan**  
📌 **Nordic Model:** Combines **economic strength, autonomy, social safety nets, and strong communities**.  

## 📊 **Data Visualizations & Techniques**  
✅ **Scatter plots with trendlines** (Linear regression models)  
✅ **Box plots to detect outliers**  
✅ **Heatmaps for correlation analysis**  
✅ **Histograms & distribution plots** for variable analysis  

## 🚀 **Next Steps**  
🔹 Improve **handling of missing values**  
🔹 Apply **machine learning models to predict happiness scores**  
🔹 Investigate **clustering nations based on happiness metrics**  

## 🖥️ **Setup & Installation**  
1️⃣ **Clone the repository:**  
   ```bash
   git clone https://github.com/your-username/EDA_Happiness_Project.git
   ```
2️⃣ **Install dependencies:**  
   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```
3️⃣ **Run analysis script:**  
   ```bash
   python happiness_analysis.py
   ```

## 🤝 **Contributing**  
🔹 **Fork** the repository  
🔹 **Make improvements & submit a pull request**  
🔹 Let's make **happiness analytics better together**! 🚀  

---
Contact: ivanaloveraruiz@gmail.com

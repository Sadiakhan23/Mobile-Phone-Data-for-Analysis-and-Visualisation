# 📱 Mobile-Phone-Data-for-Analysis-and-Visualisation


This project performs data cleaning, preprocessing, and exploratory data analysis (EDA) on a dataset of mobile phones. The goal is to understand relationships between specifications, pricing, ratings, and other features. <br>

📂 Project Overview<br>


The notebook analyzes a dataset containing mobile phone specifications such as:<br>


Spec Score<br>

Rating<br>

Price<br>

Processor<br>

Battery<br>

Display<br>

Camera<br>

Storage<br>

Brand / Tags<br>


We clean the dataset, handle missing values, and perform visual analysis to extract meaningful insights.<br>


📊 Dataset Information<br>

Total rows: ~1019<br>

After cleaning: ~648 rows<br>

Features: 15 columns<br>

Source: Mobile phone specifications dataset (CSV)<br>

🧹 Data Cleaning & Preprocessing<br>


Key steps performed:
<br>

Removed rows with missing processor values<br>

Dropped missing values in memoryExternal<br>

Handled missing numeric fields (Spec Score, rating, price)<br>

Stripped whitespace from text columns<br>

Ensured consistent formatting across features<br>

📈 Exploratory Data Analysis (EDA)<br>


The following visualisations were performed:<br>


1. Distribution Analysis<br>

Spec Score distribution<br>

Rating distribution<br>

Price distribution<br>

2. Categorical Analysis<br>

Count of mobile phone tags (e.g., LAUNCHED, UPCOMING, RUMORED)<br>

3. Relationships Between Variables<br>

Pairplot of:<br>

Spec Score<br>

Rating<br>

Price<br>

4. Outlier Detection<br>

Boxplot for price distribution<br>

5. Correlation Analysis<br>

Heatmap of numerical features:<br>

Spec Score<br>

Rating<br>

Price<br>

📌 Key Insights<br>

1. Most phones fall in the mid-price range (10,000–35,000)<br>

2. Spec Score and Rating show a positive relationship<br>

3. High-end devices significantly increase price variance<br>

4. Dataset contains noticeable outliers in pricing<br>

# 🛠️ Tech Stack<br>

1.Python 🐍<br>

2.Pandas<br>

3.NumPy<br>

4.Matplotlib<br>

5.Seaborn<br>

6. Google Colab<br>

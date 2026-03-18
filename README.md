# 🧠 Customer Segmentation Using Unsupervised Learning

## 📌 Objective
The objective of this project is to segment customers based on their demographic and spending behavior using unsupervised learning techniques. This helps businesses understand customer groups and design targeted marketing strategies.

---

## 📊 Dataset
The dataset used in this project is the **Mall Customers Dataset**, which contains the following features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

---

## ⚙️ Approach

The project follows a structured data analysis workflow:

1. **Data Loading**
   - Imported dataset using Pandas

2. **Data Cleaning & Preprocessing**
   - Renamed incorrect column (Genre → Gender)
   - Removed unnecessary columns (CustomerID)
   - Converted categorical data into numerical format

3. **Exploratory Data Analysis (EDA)**
   - Analyzed distributions of Age, Income, and Spending Score
   - Visualized relationships using scatter plots

4. **Feature Scaling**
   - Applied StandardScaler to normalize data

5. **K-Means Clustering**
   - Used Elbow Method to find optimal clusters
   - Applied K-Means with 5 clusters

6. **Dimensionality Reduction**
   - Used PCA to visualize clusters in 2D space

---

## 📈 Results and Findings

- Identified **5 distinct customer segments**
- Clear patterns observed between income and spending behavior
- PCA visualization confirmed well-separated clusters

---

## 🎯 Key Insights

- High-income customers with high spending are ideal targets for premium services
- Low-income groups respond better to discounts and offers
- Young customers show higher spending trends
- Some high-income customers spend less and need targeted marketing

---

## 🚀 Conclusion

Customer segmentation using K-Means clustering provides valuable insights into customer behavior. Businesses can leverage these insights to improve marketing strategies, enhance customer experience, and increase revenue.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📁 Project Structure

# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Description
In this project, I used K-Means Clustering (an unsupervised machine learning algorithm) to understand customer behavior. By analyzing factors like annual income and spending score, I grouped customers into different segments. This kind of segmentation can help businesses better understand their customers and make smarter marketing decisions.

---

## 🎯 Problem Statement
Understanding customer behavior is not always straightforward. Businesses often have data but don’t know how to use it effectively.  
This project focuses on:
- Discovering patterns in customer data  
- Grouping customers with similar behaviors  
- Helping businesses target the right audience  

---

## 📂 Dataset Information
The dataset is sourced from Kaggle.
from here: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python
- Dataset: Mall Customers Dataset  
- Total Records: 200  
- Features included:
  - Customer ID  
  - Gender  
  - Age  
  - Annual Income (k$)  
  - Spending Score (1–100)  

---

## 🛠️ Technologies Used
- Python  
- Pandas (for data handling)  
- Matplotlib (for visualization)  
- Scikit-learn (for machine learning)  
- Jupyter Notebook  

---

## ⚙️ Approach
Here’s how I built the project step by step:

1. Imported all the required libraries  
2. Loaded and explored the dataset  
3. Visualized the relationship between income and spending  
4. Selected relevant features for clustering  
5. Used the Elbow Method to find the optimal number of clusters  
6. Applied K-Means clustering  
7. Visualized the final clusters along with their centroids  

---

## 📊 Results
The model grouped customers into **5 different clusters**, each representing a specific type of customer behavior.

---

## 📈 Key Insights
Some interesting patterns I found:
- Customers with high income and high spending are ideal premium targets  
- High income but low spending customers could be encouraged with better offers  
- Low income but high spending customers are valuable but unpredictable  
- Low income and low spending customers are more budget-focused  

---

## 🚀 How to Run
1. Clone or download this project  
2. Install the required libraries:
   ```
   pip install pandas matplotlib scikit-learn
   ```
3. Open the notebook using Jupyter  
4. Run all the cells step by step  

---

## 📸 Output
- A clear visualization of customer segments  
- Each cluster is color-coded for easy understanding  
- Cluster centroids are also highlighted  

---

## ⚠️ Limitations
- Only two features were used, so insights are somewhat limited  
- K-Means assumes clusters are evenly shaped, which may not always be true  

---

## 🔮 Future Improvements
- Include more features for better analysis  
- Try other clustering algorithms like Hierarchical Clustering  
- Build a simple web app to interact with the model  

---

## 👨‍💻 Author
Chethan

---

## ⭐ Resume Highlight
Built a customer segmentation model using K-Means clustering to identify 5 distinct customer groups and extract actionable business insights.
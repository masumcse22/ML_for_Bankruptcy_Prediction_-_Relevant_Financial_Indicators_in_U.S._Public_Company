# ML for Bankruptcy Prediction: Relevant Financial Indicators in U.S. Public Companies  

![Cover](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.statista.com%2Fchart%2F22563%2Fbankruptcies-in-the-us%2F&psig=AOvVaw23fEqVtUPWQJ-T2D2mvCM5&ust=1735280243641000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCMiClqLlxIoDFQAAAAAdAAAAABAE)

## 🚀 Project Overview  
This project focuses on leveraging **machine learning** to predict the likelihood of bankruptcy in U.S. public companies using key financial indicators. By utilizing historical financial data and advanced classification algorithms, this project aims to provide actionable insights for **financial analysts**, **investors**, and **business decision-makers**.  

Bankruptcy prediction is crucial for mitigating risks, optimizing investments, and ensuring financial stability. This tool seeks to serve as an early warning system, helping stakeholders make informed decisions.  

---

## 📊 Key Objectives  
- Develop a reliable **machine learning pipeline** to predict bankruptcy.  
- Analyze and select **relevant financial indicators** that significantly influence bankruptcy.  
- Evaluate and compare multiple classification algorithms for accuracy and efficiency.  

---

## 🔍 Dataset  
The dataset comprises historical financial data of U.S. public companies, including indicators such as:  
- **Debt-to-Equity Ratio**  
- **Return on Assets (ROA)**  
- **Net Profit Margin**  
- **Operating Cash Flow Ratio**  
- **Earnings Per Share (EPS)**  
- **Working Capital Ratio**  

The dataset also includes the target variable indicating bankruptcy status (`Bankruptcy: Yes/No`).  

---

## 🛠️ Technologies Used  
- **Python**: Core programming language for implementation.  
- **Pandas**: For data manipulation and analysis.  
- **Scikit-learn**: For building and evaluating machine learning models.  
- **Matplotlib & Seaborn**: For data visualization and insights.  
- **NumPy**: For numerical operations.  
- **MLflow/DVC (optional)**: For managing the ML lifecycle and versioning datasets/models.  

---

## 🧠 Machine Learning Workflow  

### 1️⃣ **Data Preprocessing**  
- Handling missing values.  
- Encoding categorical features.  
- Standardizing financial indicators for uniformity.  

### 2️⃣ **Feature Selection**  
- Correlation analysis to identify significant features.  
- Principal Component Analysis (PCA) for dimensionality reduction (if necessary).  

### 3️⃣ **Model Development**  
Several classification algorithms were implemented and compared:  
- Logistic Regression  
- Decision Trees  
- Random Forest  
- Gradient Boosting (e.g., XGBoost, LightGBM)  
- Support Vector Machines (SVM)  
- Neural Networks (if applicable)  

### 4️⃣ **Model Evaluation**  
Models were evaluated based on:  
- Accuracy  
- Precision, Recall, F1-Score  
- Area Under Curve (AUC-ROC)  

---

## 📈 Results  
The project achieved significant accuracy with the **[best-performing algorithm]**, demonstrating its capability to predict bankruptcy effectively. Key insights include:  
- **[Highlight key findings, e.g., "Debt-to-Equity Ratio was the most influential predictor."]**  
- **[Mention any unexpected trends, e.g., "Higher EPS values did not significantly reduce bankruptcy risk."]**  

---

## 🌟 Key Takeaways  
- Early detection of financial distress is critical for risk mitigation.  
- Machine learning models outperform traditional statistical methods in bankruptcy prediction.  
- Identifying relevant financial indicators helps streamline the prediction process.  

---

## 📚 Future Work  
- Incorporate more **external financial indicators** like market sentiment and macroeconomic factors.  
- Expand analysis to include **global companies**.  
- Integrate the model into a **real-time financial analysis platform**.  

---

## 📝 License  
This project is licensed under the **MIT License** – feel free to use and modify it for your own projects!  

---

## 🤝 Acknowledgments  
Special thanks to:  
- for providing the dataset.  
- Open-source tools and libraries that made this project possible.  

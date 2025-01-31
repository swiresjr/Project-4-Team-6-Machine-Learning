# 📊 Predicting College Student Dropouts with Machine Learning

## **Overview**
This project applies **machine learning** to predict **student outcomes** (Dropout, Enrolled, Graduated) based on **academic, demographic, and socioeconomic data**. The dataset was obtained from the **UC Irvine Machine Learning Repository** and is used to develop models that can help **higher education institutions** identify at-risk students and improve retention strategies.

## **Objective**
- Predict whether a student will **Dropout, Stay Enrolled, or Graduate** using machine learning.
- Analyze **key factors** influencing student success.
- Address **class imbalance** to improve predictive accuracy.
- Provide **actionable insights** for educational institutions.

## **Target Audience**
🎓 **Higher Education Institutions** (Administrators, Policymakers)  
🏛 **Government & Educational Policy Makers** (Specialists, Designers)  
💻 **EdTech Companies** (Developers, Analysts)  

## **Dataset**
- **Source**: UC Irvine Machine Learning Repository  
- **Link**: [Predict Students Dropout and Academic Success Dataset](https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success)  
- **Features**: Academic performance, previous qualifications, demographics, socioeconomic factors.  

## **Machine Learning Models Used**
✅ **Random Forest**  
✅ **Neural Network**  
✅ **Logistic Regression**  
✅ **Decision Tree**  

## **Key Findings**
🔹 **Overall Accuracy:** **75%** (Random Forest, Logistic Regression, and Decision Tree).  
🔹 **Best Performance:** **Graduates (Class 2) - 85% Recall**  
🔹 **Challenges:** Misclassification of Dropouts (e.g., **54 misclassified as Enrolled, 33 as Graduates**).  

## **Feature Insights**
### **Strongest Predictors (Positive Correlation)**  
✔ **Curricular Units (S1 & S2):** Higher approval rates correlate with success.  
✔ **Admission Grade:** Strong correlation with student retention.  

### **Risk Factors for Dropout (Negative Correlation)**  
⚠ **Age at Enrollment, Debt Status, Gender** – Older students and those with financial struggles are more likely to drop out.  
⚠ **Previous & Parental Qualifications** – Lower education levels may indicate weaker academic foundations.  

## **Model Performance Analysis**
📉 **Training Accuracy:** **92%**, but validation accuracy remains at **75%** → Suggesting **overfitting**.  
📊 **Validation Accuracy Plateaus** despite increasing dataset size.  

## **Recommendations for Improvement**
🔹 **Collect More Data** → Include behavioral & financial indicators.  
🔹 **Factor in Financial Situations** → Consider **credit score, student employment, financial aid sources**.  
🔹 **Calculate Credit Hours Per Semester** → Helps track student workload.  
🔹 **Reduce Target Outcomes** → Dropping the **"Enrolled" category** may increase accuracy to **95%**.  

## **Next Steps**
- **Feature Engineering**: Create new meaningful predictors.  
- **Hyperparameter Tuning**: Optimize models to reduce overfitting.  
- **Alternative Models**: Test **Gradient Boosting, XGBoost, and Ensemble Learning** for better results.  

## **Contributors**
👤 **Carissa Guzman**  
👤 **Christopher Swires**  
👤 **Cristian Waitman**  
👤 **Phung Huynh**  
👤 **Dahlia Segarra**  

## **Acknowledgment**
Special thanks to the **UC Irvine Machine Learning Repository** for providing the dataset.

# **Fake Job Posting Detection**

## **📌 Project Overview**
This project focuses on detecting fraudulent job postings using **machine learning** and **data visualization** techniques. The dataset is preprocessed, analyzed, and used to train models that classify job postings as *real* or *fake*. Additionally, a **Excel dashboard** is created to visualize key insights and patterns in job fraud cases.

---

## **📂 Dataset Used**
- **File:** `fake_job_postings.csv` (Raw, uncleaned dataset)  
- **Features Include:**  
  - *Title, Company, Location, Department, Salary, Job Type, Required Education, Industry, and Description*  
  - A *fraudulent* column indicating whether the job post is fake (1) or real (0).

---

## **🛠 Data Processing Steps**

### **1️⃣ Data Cleaning & Preprocessing**
- Handled missing values and standardized text data.  
- Performed feature engineering (text vectorization, encoding categorical variables).  
- Exploratory Data Analysis (EDA) to understand **fraudulent job trends**.

---

### **2️⃣ SQL Integration & Storage**
- **Connected Python to SQL using SQLAlchemy** for structured storage.
- Stored the processed data in a **SQL database** for efficient querying and analysis.
- Used **SQL queries** to extract insights on fraud trends and job categories.

---

### **3️⃣ Machine Learning Model**
- Used **TF-IDF** for text feature extraction.  
- Trained classifiers like **Logistic Regression, Random Forest, and XGBoost**.  
- Evaluated models using accuracy, precision, recall, and F1-score.

---

### **4️⃣ Excel Dashboard**
- Created an **interactive dashboard** to analyze fraud patterns.  
- **Visuals include:**  
  - Fraud distribution by **experience level, job type, and industry**.  
  - **Geographical trends** in fraudulent job postings.  
  - **Comparison of fake vs. real job postings** across multiple dimensions.

---

## **🔧 Tools & Technologies**
- **Python:** Pandas, NumPy, Scikit-Learn, NLTK, SQLAlchemy  
- **Database:** MySQL / PostgreSQL (Connected via SQLAlchemy)  
- **Machine Learning Models:** Logistic Regression, Random Forest, XGBoost  
- **Visualization:** Power BI, Matplotlib, Seaborn  

---

## **📁 Repository Structure**
```
📂 Fake-Job-Detection  
│── 📁 data  
│   ├── fake_job_postings.csv  # Raw dataset  
│   ├── cleaned_data.csv  # Processed dataset  
│── 📁 notebooks  
│   ├── 01_EDA.ipynb  # Exploratory Data Analysis  
│   ├── 02_SQL_Storage.ipynb  # SQL Connection & Queries  
│   ├── 03_ML_Modeling.ipynb  # Machine Learning Model  
│── 📁 dashboard  
│   ├── Job_Fraud_Analysis.pbix  # Power BI Dashboard  
│── README.md  # Project Documentation  
```

---

## **🚀 Getting Started**

### **🔹 Installation**
1️⃣ Clone the repository:  
```bash
git clone https://github.com/mohammadasifa/Fake-Job-Posting-Analysis.git
```
2️⃣ Install dependencies:  
```bash
pip install pandas numpy scikit-learn nltk matplotlib seaborn sqlalchemy mysql-connector-python
```
3️⃣ Run Jupyter Notebook to explore data, store it in SQL, and train models.  

---

## **📊 Results & Insights**
- **Key Indicators of Fake Job Postings:**  
  - **Missing company logos** in job postings.  
  - **Unclear job descriptions** and vague job requirements.  
  - **Industries with high fraud risk:** Oil & Energy, Marketing, and Real Estate.  

- **Machine Learning Model Performance:**  
  - Achieved **96% accuracy** in detecting fraudulent job postings.  

---

## **💡 Future Improvements**
✅ Improve feature extraction using **word embeddings (Word2Vec, BERT)**.  
✅ Expand dataset with more real-world job postings for better generalization.  
✅ Deploy a **real-time fraud detection API**.  

---

#### **📊 Dashboard Preview**
![Dashboard Preview](https://github.com/yourusername/Fake-Job-Detection/blob/main/assets/dashboard.png)

---

## **🙌 Contributor**
👤 **Mohammad Asif** – *Data Analysis, SQL Integration & Model Training*  

---

## **📜 License**
This project is **open-source** under the MIT License.  

---

### **🌟 Star this repository if you found it useful! 🚀**

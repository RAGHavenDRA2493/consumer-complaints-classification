# 📌 Consumer Complaints Classification

## 🔍 Project Overview
This project classifies consumer complaints into predefined categories using **Natural Language Processing (NLP)** and **Machine Learning (ML)** models. The dataset is sourced from the [Consumer Complaint Database](https://catalog.data.gov/dataset/consumer-complaint-database).

## 📂 Dataset
The dataset contains consumer complaints and includes fields such as:
- **Date received**  
- **Product (Type of complaint)**  
- **Issue (Details about the complaint)**  
- **Consumer complaint narrative (Text description of complaint)**  
- **Company response**  
- **Complaint ID**  

We classify complaints into the following categories:
- **0**: Credit reporting, credit repair services, or other personal consumer reports  
- **1**: Debt collection  
- **2**: Consumer Loan  
- **3**: Mortgage  

## 🚀 Methodology
1. **Data Preprocessing**:
   - Removed null values.
   - Combined similar complaint categories.
   - Converted text data into TF-IDF features.
   - Balanced classes using undersampling.

2. **Model Training**:
   - **Naive Bayes**
   - **Logistic Regression**
   - **Random Forest**
   - **Support Vector Machine (SVM)** (Fine-tuned)

3. **Evaluation**:
   - Compared models using **Accuracy, Precision, Recall, and F1-score**.

---

## 🛠️ Installation & Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/consumer-complaints-classification.git
   cd consumer-complaints-classification

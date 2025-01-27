# Customer Data Analysis and Machine Learning Tasks

This repository contains the implementation of customer data analysis and machine learning tasks. The project includes exploratory data analysis (EDA), a lookalike model, and customer segmentation using clustering techniques.

---

## **Project Overview**

### **1. Task 1: Exploratory Data Analysis (EDA)**
**Objective:**  
Analyze customer transaction data to derive actionable business insights.

**Deliverables:**  
- **Jupyter Notebook/Python Script:** `BHARATHI_S_EDA.ipynb`
- **PDF Report:** `BHARATHI_S_EDA.pdf`

**Highlights:**
- Region-wise analysis of customer activity.
- Popular product categories identified.
- Seasonal sales trends analyzed.
- Business recommendations provided based on insights.

---

### **2. Task 2: Lookalike Model**
**Objective:**  
Develop a model to recommend the top 3 similar customers for a given customer based on their profile and transaction history.

**Deliverables:**  
- **Jupyter Notebook/Python Script:** `BHARATHI_S_Lookalike.ipynb`
- **CSV Output:** `BHARATHI_S_Lookalike.csv`
- **PDF Report:** `BHARATHI_S_Lookalike.pdf`

**Methodology:**
- Created features from transaction data.
- Used **Cosine Similarity** for similarity computation.
- Generated recommendations for the first 20 customers (`CustomerID: C0001 - C0020`).

---

### **3. Task 3: Customer Segmentation**
**Objective:**  
Perform clustering to segment customers into distinct groups for targeted strategies.

**Deliverables:**  
- **Jupyter Notebook/Python Script:** `BHARATHI_S_Clustering.ipynb`
- **CSV Output:** `BHARATHI_S_Clustering.csv`
- **PDF Report:** `BHARATHI_S_Clustering.pdf`

**Methodology:**
- Combined profile and transaction data.
- Used **K-Means clustering** to segment customers.
- Evaluated clustering performance with the **Davies-Bouldin Index (DB Index)**.
- Visualized clusters using relevant plots.

**Results:**
- Optimal number of clusters identified using the DB Index.
- Customer segmentation revealed actionable insights.

---

## **Setup and Requirements**

### **Prerequisites**
- Python 3.8 or above
- Jupyter Notebook

### **Libraries Used**
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`

### **Installation**
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/customer-data-analysis.git

2. Navigate to the project directory:
   ```bash
   cd customer-data-analysis

3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt

4. Run the Jupyter Notebooks:
    ```bash
   jupyter notebook






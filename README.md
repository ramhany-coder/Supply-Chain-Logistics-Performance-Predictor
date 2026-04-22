# Supply Chain Logistics Prediction using Logistic Regression

This project analyzes supply chain logistics data to predict shipping performance. Specifically, it uses **Logistic Regression** to classify the "Ship ahead day count" based on various operational features like carriers, ports, and product specifications.

## 📊 Dataset Overview
The project processes a logistics dataset (`Supply chain logisitcs problem.xlsx`) containing 9,215 entries and 14 primary columns. Key features include:
* **Logistics Info:** Origin Port, Destination Port, Carrier, and Service Level.
* **Product Details:** Product ID, Unit Quantity, and Weight.
* **Temporal Data:** Order Date and Transit Processing Time (TPT).
* **Target Variable:** `Ship ahead day count` (Categorized performance metrics).

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib.

## 🚀 Key Features
1. **Data Preprocessing:** - Automated identification of categorical (53.85%) and numerical (46.15%) features.
   - Handling of high-cardinality features like `Product ID` and `Customer`.
2. **Feature Engineering:**
   - Analysis of feature ranges and unique types across the dataset.
   - Target separation and data cleaning.
3. **Machine Learning Pipeline:**
   - Implementation of a **Logistic Regression** classifier.
   - Data splitting for training and validation.
4. **Performance Evaluation:**
   - Detailed **Classification Report** (Precision, Recall, F1-Score).
   - Visual **Confusion Matrix** heatmap for multi-class performance analysis.

## 📈 Results
The model's performance is evaluated using standard metrics to ensure reliability in predicting whether shipments will be ahead of schedule, helping logistics managers optimize warehouse and carrier selection.

## 📂 Project Structure
- `supplychain.ipynb`: The main Jupyter notebook containing the analysis and model.
- `Supply chain logisitcs problem.xlsx`: (Not included/Add your data source here).

## 📝 How to Use
1. Clone the repository.
2. Install dependencies: `pip install pandas scikit-learn seaborn`.
3. Run the `supplychain.ipynb` notebook.

# 🌌 Celestial Object Classification using Machine Learning

## 📌 Project Overview

The **Celestial Object Classification using Machine Learning** project focuses on automatically identifying and classifying astronomical objects such as **Stars, Galaxies, and Quasars** using observational data collected from sky surveys. By leveraging machine learning algorithms and astrophysical features including photometric measurements and redshift values, the system accurately predicts the type of celestial object present in the dataset.

This project demonstrates the complete machine learning pipeline, including data preprocessing, exploratory data analysis, feature engineering, dimensionality reduction, model training, evaluation, and visualization.

---

## 🎯 Objectives

* Classify celestial objects into Stars, Galaxies, and Quasars.
* Analyze astronomical features and their impact on classification.
* Compare the performance of multiple machine learning models.
* Reduce feature dimensionality using Principal Component Analysis (PCA).
* Visualize astronomical data patterns and model performance.

---

## 📂 Dataset Description

The dataset contains astronomical observations obtained from sky surveys and includes:

| Feature       | Description                                          |
| ------------- | ---------------------------------------------------- |
| RA            | Right Ascension coordinate                           |
| DEC           | Declination coordinate                               |
| u, g, r, i, z | Photometric magnitudes in different wavelength bands |
| Redshift      | Measure of object distance and velocity              |
| Class         | Target variable (Star, Galaxy, Quasar)               |

### Target Classes

* ⭐ Star
* 🌌 Galaxy
* ✨ Quasar

---

## ⚙️ Machine Learning Pipeline

### 1. Data Collection

* Imported celestial observation dataset.
* Loaded data using Pandas.

### 2. Data Preprocessing

* Handled missing values.
* Removed duplicate records.
* Encoded categorical labels.
* Performed feature scaling using StandardScaler.

### 3. Exploratory Data Analysis (EDA)

* Class distribution analysis.
* Correlation heatmap.
* Photometric band visualization.
* Feature relationship analysis.
* Outlier detection.

### 4. Feature Engineering

* Selected relevant astronomical features.
* Standardized numerical variables.
* Prepared data for model training.

### 5. Dimensionality Reduction

Applied **Principal Component Analysis (PCA)** to:

* Reduce feature dimensionality.
* Improve computational efficiency.
* Visualize celestial object clusters.

### 6. Model Training

Implemented and compared multiple machine learning algorithms:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* XGBoost Classifier

### 7. Model Evaluation

Performance evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

---

## 📊 Visualizations

The project includes several visualizations for better understanding of astronomical data:

### Data Analysis

* Class Distribution Plot
* Photometric Band Boxplots
* Correlation Heatmap
* Pairwise Feature Analysis

### Dimensionality Reduction

* PCA Scatter Plot

### Model Performance

* Accuracy Comparison Chart
* Precision Comparison Chart
* Recall Comparison Chart
* F1-Score Comparison Chart
* Confusion Matrix Visualization

---

## 🛠 Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

### Development Environment

* Google Colab
* Jupyter Notebook

---

## 📈 Results

* Successfully classified celestial objects into Stars, Galaxies, and Quasars.
* Identified significant astronomical features influencing classification.
* Applied PCA for dimensionality reduction and visualization.
* Compared multiple machine learning algorithms.
* Achieved high classification accuracy using the best-performing model.
* Demonstrated the effectiveness of machine learning in astronomical object recognition.

---

## 🚀 Future Enhancements

* Integrate Deep Learning models such as CNNs and Neural Networks.
* Perform real-time celestial object classification.
* Utilize larger astronomical datasets from modern sky surveys.
* Develop a web-based astronomical classification dashboard.
* Implement automated hyperparameter optimization.

---

## 📁 Project Structure

```text
Celestial-Object-Classification/
│
├── dataset/
│   └── celestial_data.csv
│
├── notebooks/
│   └── celestial_classification.ipynb
│
├── images/
│   ├── class_distribution.png
│   ├── correlation_heatmap.png
│   ├── pca_scatter_plot.png
│   └── model_comparison.png
│
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/celestial-object-classification.git
```

2. Navigate to the project directory

```bash
cd celestial-object-classification
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Open the notebook

```bash
jupyter notebook
```

5. Run all cells to reproduce results.

---

## 💡 Applications

* Astronomical Survey Analysis
* Space Object Identification
* Sky Mapping Systems
* Astrophysics Research
* Automated Observatory Pipelines
* Scientific Data Mining

---

## 👩‍💻 Author

**Padmaja Deshmukh**

Machine Learning Enthusiast | Data Science | Artificial Intelligence

---

## 📜 License

This project is developed for educational and research purposes.

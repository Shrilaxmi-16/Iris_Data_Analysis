# Iris_Data_Analysis

# Create README.md file for the project
readme_content = """
# Iris Dataset Classification using KNN  

This project demonstrates **data analysis, preprocessing, and classification** on the famous **Iris dataset**. We use **K-Nearest Neighbors (KNN)** as the classifier, experiment with different values of *K*, evaluate the model, and visualize the decision boundaries.  

---

## 📌 Steps Performed  

### 1. Exploratory Data Analysis (EDA)  
- Loaded the Iris dataset (`Iris.csv`).  
- Checked dataset info, summary statistics, and class distribution.  
- Plotted **pair plots** and **correlation heatmap** to study feature relationships.  

### 2. Data Preprocessing  
- Dropped unnecessary columns (`Id`).  
- Normalized numerical features using **StandardScaler**.  
- Encoded the target variable (`Species`).  
- Split data into **train (80%)** and **test (20%)** sets.  

### 3. Classification using KNN  
- Trained **KNeighborsClassifier** with different values of `K` (1, 3, 5, 7, 9, 11).  
- Compared **accuracy scores** for each K.  
- Evaluated models using:  
  - Accuracy Score  
  - Confusion Matrix  
  - Classification Report  

### 4. Visualization  
- **Accuracy vs K plot** to see performance trend.  
- **Decision Boundaries**:  
  - Using raw features (**Sepal Length & Sepal Width**).  
  - Using all 4 features reduced to 2D with **PCA**.  
- Compared both decision boundaries side-by-side with accuracy scores.  

---

## 📊 Results  

- Accuracy varied slightly with different `K` values, with **K=5** giving stable results.  
- PCA-based visualization captured better class separations compared to raw features.  
- Decision boundaries clearly show the separation between **Setosa, Versicolor, and Virginica**.  

---

## 🛠️ Technologies Used  
- Python  
- Pandas, NumPy  
- Scikit-learn (KNeighborsClassifier, StandardScaler, PCA)  
- Matplotlib, Seaborn  

---

## 📷 Sample Visualizations  

- Pairplot of features  
- Correlation heatmap  
- Accuracy vs K curve  
- Decision boundary plots:  
  - Raw features vs PCA features  

---

## 🚀 How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/iris-knn-classification.git
   cd iris-knn-classification

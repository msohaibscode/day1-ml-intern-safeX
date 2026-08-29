# 🌸 Iris Flower Classification – Machine Learning

A beginner-friendly Machine Learning project that predicts the species of an Iris flower using its sepal and petal measurements.

This project demonstrates the basic Machine Learning workflow:

**Dataset → Data Preparation → Model Training → Prediction → Evaluation → Visualization**

---

## 📌 Project Overview

The goal of this project is to build a Machine Learning model that can classify an Iris flower into one of three species:

* 🌸 Setosa
* 🌼 Versicolor
* 🌺 Virginica

The model uses four features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

---

## 🧠 Machine Learning Model

This project uses a **Logistic Regression** classification model.

The model learns patterns from the Iris dataset and predicts the flower species based on the input measurements.

### Input

```text
Sepal Length
Sepal Width
Petal Length
Petal Width
```

### Output

```text
0 → Setosa
1 → Versicolor
2 → Virginica
```

---

## 📊 Dataset

The project uses the **Iris Dataset**, a popular dataset for learning Machine Learning.

The dataset contains:

* **150 samples**
* **4 input features**
* **3 flower classes**
* **50 samples per class**

### Features

| Feature      | Description         |
| ------------ | ------------------- |
| Sepal Length | Length of the sepal |
| Sepal Width  | Width of the sepal  |
| Petal Length | Length of the petal |
| Petal Width  | Width of the petal  |

### Classes

| Class | Flower     |
| ----- | ---------- |
| 0     | Setosa     |
| 1     | Versicolor |
| 2     | Virginica  |

---

## 🛠️ Technologies Used

* Python
* Google Colab
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Git
* GitHub

---

## 📁 Project Structure

```text
day1_iris_classification/
│
├── iris_classification.ipynb
├── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/day1-ml-intern-safeX.git
```

Move into the project directory:

```bash
cd iris-flower-classification
```

Install the required libraries:

---

## 📦 Requirements

The project requires the following Python libraries:

```text
numpy
pandas
scikit-learn
matplotlib
seaborn
```

---

## 🚀 How to Run

### Option 1 – Google Colab

Open the `.ipynb` file in Google Colab and run the cells sequentially.

### Option 2 – Jupyter Notebook

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
iris_classification.ipynb
```

Run all cells.

---

## 🔄 Machine Learning Workflow

### 1. Load Dataset

The Iris dataset is loaded using Scikit-learn.

### 2. Prepare the Data

The dataset is divided into:

* Features (`X`)
* Target (`y`)

### 3. Split the Dataset

The data is divided into training and testing sets.

```text
Training Data → Model Learning
Testing Data  → Model Evaluation
```

### 4. Train the Model

Logistic Regression is trained using the training data.

### 5. Make Predictions

The trained model predicts the flower class for unseen data.

### 6. Evaluate the Model

The model's performance is evaluated using accuracy.

### 7. Visualize the Results

Graphs are used to understand the dataset and model results.

---

## 📈 Model Performance

The model achieved:

```text
Accuracy: 1.0
```

This means the model correctly classified **100% of the samples in the evaluated test set**.

> Note: Accuracy can vary depending on the train/test split and random state.

---

## 🔮 Example Prediction

Example input:

```python
sample = [[5.1, 3.5, 1.4, 0.2]]
```

Prediction:

```text
Predicted class: 0
Predicted flower: Setosa
```

---

## 📊 Visualization

The project includes visualizations to understand the Iris dataset and classification results.

Example visualizations include:

* Feature relationships
* Flower class distribution
* Classification-related plots

---

## 🎯 Learning Objectives

This project was created to understand the fundamentals of Machine Learning, including:

* Understanding datasets
* Feature and target variables
* Data splitting
* Model training
* Classification
* Making predictions
* Model evaluation
* Accuracy
* Data visualization
* Using Scikit-learn
* Saving ML projects on GitHub

---

## 🔮 Future Improvements

The project can be improved by:

* Trying different Machine Learning algorithms
* Comparing Logistic Regression, Decision Tree, KNN and Random Forest
* Adding a confusion matrix
* Adding more evaluation metrics
* Creating a Streamlit web application
* Deploying the model online
* Saving the trained model using Joblib
* Creating an API using FastAPI

---

## 👨‍💻 Author

**Sohaib**

Software Engineering Student | AI & Machine Learning Enthusiast

---

## ⭐ Acknowledgement

This project was created as part of a beginner Machine Learning learning journey.

If you find this project useful, consider giving the repository a ⭐ on GitHub.

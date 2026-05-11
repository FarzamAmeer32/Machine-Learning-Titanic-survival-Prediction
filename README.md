# Titanic Survival Prediction 🚢

A Machine Learning project based on the Titanic dataset from Kaggle.  
This project predicts whether a passenger survived or not using classification algorithms and preprocessing techniques.

---

# 📌 Project Overview

This notebook includes:

- Data Cleaning
- Handling Missing Values
- Feature Engineering
- Model Training
- Prediction Generation

The project was developed in Google Colab and can also be run locally in VS Code or Jupyter Notebook.

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📂 Project Structure

```text
titanic-survival/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── Titanic_model.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 📊 Dataset

Dataset used: Titanic Dataset from Kaggle

Required files:

- `train.csv`
- `test.csv`

Both dataset files are already included inside the `data/` folder so users can run the project directly without needing Google Drive.

---

# ▶️ How to Run the Project

## 1 Clone the Repository

```bash
git clone YOUR_GITHUB_REPO_LINK
cd titanic-survival
```

---

## 2 Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 3 Run the Notebook

Open:

```text
Titanic_model.ipynb
```

You can run it using:

- VS Code
- Jupyter Notebook
- Google Colab

---

# 📁 Important: Update Dataset Paths

The original notebook may contain Google Drive paths like:

```python
/content/drive/MyDrive/...
```

If running locally, replace them with:

```python
train_df = pd.read_csv("data/train.csv")
test_df = pd.read_csv("data/test.csv")
```

If running in Google Colab after uploading the dataset files manually, use:

```python
train_df = pd.read_csv("/content/train.csv")
test_df = pd.read_csv("/content/test.csv")
```

---

# 🤖 Model

The notebook trains a machine learning classification model to predict passenger survival on the Titanic dataset.

---

# 📈 Results

Achieved approximately **77% accuracy** on the Titanic Kaggle prediction task.

---

# 🚀 Future Improvements

- Hyperparameter tuning
- Better feature engineering
- Trying ensemble models
- Model deployment using Streamlit

---

# 👨‍💻 Author

Farzam Ameer

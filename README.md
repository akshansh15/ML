# ML
# 🚢 Titanic Survival Prediction - Logistic Regression

This project predicts whether a passenger survived the Titanic disaster using a **Logistic Regression** model in Python. The dataset used was taken from [Kaggle's Titanic competition](https://www.kaggle.com/c/titanic).

---

## 📁 Dataset

The data comes from Kaggle and includes:
- `train.csv`: Data with known outcomes (used to train and test the model).
- `test.csv`: Data without outcomes (used for final prediction and submission).

---

## 🔍 Objective

To build a machine learning model that predicts whether a passenger survived or not based on features like:
- **Sex**
- **Age**
- **Pclass** (passenger class)

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn

---

## ⚙️ How It Works

1. **Load and clean the data**
   - Drop irrelevant columns like `Name`, `Ticket`, and `Cabin`.
   - Handle missing values (especially in `Age`).
   - Convert categorical data (`Sex`) into numerical.

2. **Split the training data**
   - Use `train_test_split()` to create training and testing sets.

3. **Train the model**
   - Use `LogisticRegression()` from Scikit-learn.

4. **Evaluate the model**
   - Check **accuracy**, **confusion matrix**, and **classification report**.

5. **Make predictions**
   - Predict survival on the `test.csv` dataset.

6. **Export results**
   - Save predictions in `submission.csv` for submission on Kaggle.

---

## 📊 Model Performance

- **Accuracy:** ~81% on the test set (from `train.csv`)

---

## 📄 Output File

- A CSV file named `submission.csv` is created with:
  - `PassengerId`
  - `Survived` (0 = did not survive, 1 = survived)

---

## 🧠 Learnings

- Applied **logistic regression** for binary classification.
- Learned basic **data preprocessing**, **feature selection**, and **model evaluation**.
- Practiced **real-world ML pipeline** using a public dataset.

---

## ✅ To Run

```bash
1. Place 'train.csv' and 'test.csv' in the working directory.
2. Run the Python script.
3. Check 'submission.csv' for output.

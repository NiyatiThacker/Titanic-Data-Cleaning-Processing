# 🚢 Titanic Dataset: Data Cleaning & Preprocessing

This repository contains a step-by-step walkthrough of data cleaning, encoding, scaling, and outlier handling for the Titanic dataset using Python, Pandas, NumPy, Matplotlib, and Seaborn.

The project is broken into 4 well-structured Jupyter notebooks, each focused on a specific preprocessing task.

---

## 📂 Notebook Structure

### 1️⃣ `clean.ipynb`
- Load and explore the Titanic dataset
- Handle missing values in `Age`, `Embarked`, and `Cabin`
- Export the cleaned dataset
 
![Screenshot (225)](https://github.com/user-attachments/assets/9d5578eb-b888-492e-83fd-86a58773c9a1)
![Screenshot (224)](https://github.com/user-attachments/assets/c6f365f9-31d0-45fb-a750-9bcbf04b25b0)  
![Screenshot (223)](https://github.com/user-attachments/assets/65dfa6b7-322c-4522-a61a-b6514251bb2d)


---

### 2️⃣ `encode.ipynb`
- Encode `Sex` using Label Encoding
- Apply One-Hot Encoding to `Embarked`, `Pclass`, etc.
- Merge encoded columns into the dataset


![Screenshot (226)](https://github.com/user-attachments/assets/186ea9b8-5f78-43af-b05c-5e7a4317d604)


---

### 3️⃣ `Norm-Stand.ipynb`
- Apply StandardScaler on `Age`
- Apply MinMaxScaler or log transformation on `Fare`
- Visualize effects of scaling

![image](https://github.com/user-attachments/assets/a93b61a1-c7a2-40be-802d-029421bc4052)
![image](https://github.com/user-attachments/assets/4bf55f24-c803-4869-9b7f-3d30d5a48a6e)


---

### 4️⃣ `outliers.ipynb`
- Use boxplots to identify outliers in `Age`, `Fare`, `SibSp`, and `Parch`
- Remove outliers using the IQR method
- Save final cleaned dataset

![image](https://github.com/user-attachments/assets/59964be0-53b7-407a-9e59-ff323c5c1a52)


---

## 💾 Final Output

- Cleaned and outlier-free dataset: `Titanic_cleaned_no_outliers.csv`
- Ready for EDA and machine learning model training

---

## 📚 Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🙋‍♀️ Author

Created by **Niyati Thacker** — for learning and practice.

If you found this helpful, feel free to ⭐ the repo!


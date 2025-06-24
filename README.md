# 🧪 Task 2: Exploratory Data Analysis (EDA) – Titanic Dataset

## 📌 Objective
To explore and understand the Titanic dataset using **descriptive statistics** and **visualizations**, uncovering relationships, patterns, and potential feature-level insights useful for building predictive models.

---

## 🛠️ Tools & Libraries Used
- **Python**
- **Pandas** – Data handling & summary stats
- **Seaborn** – Statistical visualizations
- **Matplotlib** – Basic plotting
- **Plotly Express** – Interactive plots

---

## 📂 Dataset Description
The dataset (`Titanic-Dataset.csv`) includes passenger data from the Titanic, such as:
- **Survived** (target): 0 = No, 1 = Yes
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Sex**, **Age**, **Fare**, **SibSp**, **Parch**
- **Embarked** (C, Q, S) – encoded
- All categorical columns are encoded and missing values handled

---

## 🔍 Key Steps in EDA

### 1️⃣ Summary Statistics
- Used `.describe()` and `.value_counts()` to analyze distributions of numeric and categorical features
- Identified imbalances in gender, class, and survival rates

### 2️⃣ Visual Exploration
- **Histograms** for `Age` and `Fare` to understand distribution shape
- **Boxplots** to detect outliers in numeric columns
- **Correlation Heatmap** to study linear relationships between numeric features
- **Pairplot** to observe survival clusters across features
- **Bar Plots** for survival comparison by `Sex` and `Pclass`
- **Scatter Plot** (`Fare` vs `Age`) using Plotly for interactive analysis

---

## 📈 Feature-Level Inferences

| Feature    | Insight |
|------------|---------|
| **Sex**     | Females had significantly higher survival rates |
| **Pclass**  | 1st class passengers had highest survival |
| **Age**     | Young children had better survival chances |
| **Fare**    | Higher fare → higher probability of survival |
| **Correlation** | `Fare` and `Survived` had positive correlation; `Sex` (encoded) negatively correlated with `Survived` |

---

## 🧠 Insights & Observations
- Gender and class are strong indicators of survival.
- Visuals revealed clear separation between survivors and non-survivors across some features.
- Outliers exist in `Fare` and `Age`, which may affect model training if not handled.

---

## 📁 Files Included
- `Titanic-Dataset.csv` – Preprocessed dataset
- `day2-elevate-labs.ipynb` – Jupyter/Colab notebook for EDA
- `day2-elevate-labs.py` - Python source file for automation
- `README.md` – This documentation file

---

## 🚀 Next Steps
- Proceed to Feature Engineering or Modeling (e.g., logistic regression, decision trees)
- Use insights gained here to select and prioritize features

---

OUTPUTS
---

![Screenshot 2025-06-24 151722](https://github.com/user-attachments/assets/6d879304-bcd1-4038-9c13-a687a562ff68)

![Screenshot 2025-06-24 151723](https://github.com/user-attachments/assets/8bafded1-728a-49f7-9626-832ee84b43eb)

![Screenshot 2025-06-24 151736](https://github.com/user-attachments/assets/4000915a-4f3a-400f-b511-9c5f9f029d95)

![Screenshot 2025-06-24 151756](https://github.com/user-attachments/assets/053369de-9ff6-4d3b-b2ae-30928855bae4)

![Screenshot 2025-06-24 151833](https://github.com/user-attachments/assets/c8235226-1154-4fb3-9b2b-27a7b29f1d01)

![Screenshot 2025-06-24 151924](https://github.com/user-attachments/assets/3d26c845-60e4-486c-8fe9-93451ccf2b3b)

![Screenshot 2025-06-24 151944](https://github.com/user-attachments/assets/d2e44d23-4760-490e-a1ed-788517d89fac)

![Screenshot 2025-06-24 152001](https://github.com/user-attachments/assets/318eab33-770b-4714-9bdf-6bc84ad614e7)

![Screenshot 2025-06-24 152013](https://github.com/user-attachments/assets/26a5edca-e2f0-4087-b97a-9c0b2ab4c73b)

![Screenshot 2025-06-24 152024](https://github.com/user-attachments/assets/81b8c9cb-69fa-4227-a950-ffcd53835ef8)

# wrapper-methods
# 🧠 Wrapper Methods for Feature Selection

This project demonstrates how **wrapper methods** can be used to improve model performance by selecting an optimal subset of features when predicting **obesity** based on eating habits and lifestyle factors. 

It explores:
- Sequential Forward Selection (SFS)
- Sequential Backward Floating Selection (SBFS)
- Recursive Feature Elimination (RFE)

All methods are benchmarked against a baseline logistic regression model using all features.

---

## 📊 Dataset

The dataset used (`obesity_data.csv`) contains:
- Numerical features representing answers from a health survey (originally categorical and encoded).
- A target label: `"NObeyesdad"` with classes such as `"Obese"`, `"Overweight"`, `"Normal"`.

---

## ⚙️ Technologies

- Python 3.9+
- Pandas
- Scikit-learn
- MLXtend
- Pytest (for testing)

---

## 📦 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/wrapper-methods-obesity.git
cd wrapper-methods-obesity
pip install -r requirements.txt

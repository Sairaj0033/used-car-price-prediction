# 🚗 Used Car Price Prediction

A machine learning project to predict the selling price of a used car based on features such as brand, fuel type, transmission, ownership, and more. The model is trained using a Random Forest Regressor and includes proper preprocessing and label encoding.

---

## 🧱 Project Structure

```

used-car-price-prediction/
│
├── data/              # Dataset files
│   └── cars.csv
│
├── models/            # Trained model and preprocessing objects
│   ├── Rf.joblib
│   ├── scalerX.joblib
│   ├── scalery.joblib
│   ├── Lbl\_brand.joblib
│   ├── Lbl\_fuel.joblib
│   ├── Lbl\_owner.joblib
│   └── Lbl\_tran.joblib
│
├── notebooks/         # Jupyter notebook(s)
│   └── carPrice.ipynb
│
├── scripts/           # Python script(s) to run prediction
│   └── cars.py
│
├── requirements.txt   # List of dependencies
├── .gitignore         # Files/folders to ignore in git
└── README.md          # Project documentation (this file)

````

---

## 📥 Installation & Usage

### 1. Clone the Repository
```bash
git clone https://github.com/Sairaj0033/used-car-price-prediction.git
cd used-car-price-prediction
````

### 2. Create Virtual Environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate       # On Linux/macOS
venv\Scripts\activate          # On Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Jupyter Notebook (for training/EDA)

```bash
cd notebooks
jupyter notebook carPrice.ipynb
```

### 5. Run Python Script (for prediction)

```bash
cd scripts
python cars.py
```

---

## 💡 Model Details

* **Model Used**: Random Forest Regressor
* **Libraries**: `scikit-learn`, `pandas`, `numpy`, `joblib`
* **Preprocessing**:

  * Label Encoding: brand, fuel type, owner, transmission
  * Feature Scaling using `StandardScaler`
* **Artifacts**:

  * Trained model: `Rf.joblib`
  * Label Encoders: `Lbl_*.joblib`
  * Scalers: `scalerX.joblib`, `scalery.joblib`

---

## 📊 Dataset

* Filename: `cars.csv`
* Features:

  * `year`, `km_driven`, `fuel`, `seller_type`, `transmission`, `owner`, `brand`, `price`
* **Target Variable**: `selling_price`

> You can replace this dataset or modify the notebook to train on your own dataset.

---

## 📦 Requirements

```
pandas
numpy
scikit-learn
joblib
```

---

## 🙋‍♂️ Author

**Sairaj Shinde**
📍 Pune, India
🔗 [GitHub Profile](https://github.com/Sairaj0033)

---

## 📝 License

This project is for educational purposes. You are free to use and modify it. If you use it in your own project, a mention would be appreciated!

```

---

Let me know if you'd like to add:
- A **Streamlit interface**
- A **sample prediction example**
- A section for **"Future Improvements"**

I can include those in the README too.
```

# 🏠 PricePoint

Predict the estimated price of a property using machine learning! This project demonstrates an **end-to-end ML workflow**: data collection, preprocessing, model training, and deployment as a **CLI** tool.

---

## 🚀 Features

- Predict property prices based on:
  - Square footage
  - Number of bedrooms and bathrooms
  - Additional features like year built, lot size, etc. (optional)
- CLI-based interface: Users enter property details in the terminal and receive an estimated price.
- Modular design:
  - `train_model.py` — train and save the ML model
  - `predict_price.py` — run predictions from CLI
- Optional visualization for insights (using Matplotlib/Seaborn)

---

## 🧩 Tech Stack

- **Python 3.10+**
- **Libraries**:
  - `pandas`, `numpy` — data manipulation
  - `scikit-learn` — ML models (Linear Regression, Random Forest)
  - `joblib` — model serialization
  - `matplotlib`, `seaborn` — visualizations (optional)
- CLI interface: built-in Python `input()` and argument parsing

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
    ```bash
    git clone https://github.com/hamim23z/PropertyPricePredictor.git
    cd PropertyPricePredictor
    ```

2. **Create and activate a virtual environment**
    ```bash
    python -m venv venv
    source venv/bin/activate -> for Mac
    venv\Scripts\activate -> for Windows
    ```

3. **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the script:**
   ```bash
   python scripts/predict_price.py
   ```

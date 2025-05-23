
# stockPricePredictor

This project is designed to fetch, analyze, and visualize stock market data using Python. It uses libraries such as `pandas`, `numpy`, `matplotlib`, and `tensorflow` to process data and build machine learning models for stock price prediction.

## Features
- Download stock data for multiple companies
- Visualize stock prices and trading volume
- Build and train LSTM neural network models for forecasting
- Interactive console input for selecting stock tickers

---

## Setup Instructions PowerShell (Windows)

### 1. Create a Virtual Environment (if you don't have one already)
```powershell
py -3.10 -m venv venv
```

### 2. It's best practice to use a virtual environment to manage dependencies and isolate your project, activate the venv.
```powershell
.\venv\Scripts\activate
```

### 3. Install dependencies.
```powershell
pip install pandas numpy matplotlib seaborn tensorflow scikit-learn
```

### 4. Finally run program using the command, not run button.
```powershell
python app.py
```

### 5. Deactivate venv once done.
```powershell
deactivate
```

---

## Setup Instructions Linux

### 1. Create a Virtual Environment (if you don't have one already). Must be python3.10, not higher.
```bash
python3.10 --version
sudo apt update
sudo apt install python3.10 python3.10-venv
```

### 2. It's best practice to use a virtual environment to manage dependencies and isolate your project, activate the venv.
```bash
python3.10 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies.
```bash
pip install pandas numpy matplotlib seaborn tensorflow scikit-learn
```

### 4. Finally run program using the command, not run button.
```bash
python app.py
```

### 5. Deactivate venv once done.
```bash
deactivate
```

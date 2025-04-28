# Momentum-Plus-ML Trading Strategy

**Overview:**  
End-to-end backtest of a momentum‐plus‐machine‐learning equity strategy on the S&P 500.

## Repo structure

LICENSE README.md data/ raw/ ← raw CSVs from yfinance clean/ ← cleaned/parquet data notebooks/ ← exploratory and pipeline notebooks src/ ← code modules data_loader/ features/ strategy/ backtest/ risk/ utils/ reports/ ← plots & slide deck models/ ← saved ML models requirements.txt


## Getting started

1. Clone the repo and create a virtualenv:
   ```bash
   git clone https://github.com/<you>/<repo>.git
   cd <repo>
   python3 -m venv env
   source env/bin/activate    # or `env\Scripts\activate` on Windows

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the first notebook:
   ```bash
   jupyter notebook notebooks/01_data_ingest.ipynb



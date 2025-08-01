# StatArb-MR: Statistical Arbitrage with Mean Reversion
## 1. Project Structure
StatArb-MR/
├── data/                  # Historical price data (cached .csv)
├── notebooks/             # Jupyter notebooks for EDA & modeling
├── src/                   # Python scripts (modular)
│   ├── data_loader.py
│   ├── pair_selector.py
│   ├── mean_reversion.py
│   ├── backtest.py
│   └── utils.py
├── app/                   # Streamlit/Gradio dashboard (optional)
├── reports/               # Plots, metrics, logs
├── requirements.txt
└── README.md

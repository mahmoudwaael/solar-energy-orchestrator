# ⚡ Self-Adaptive Solar Energy Orchestrator

> An ML-powered system that learns from household energy data to generate personalized, optimal energy usage schedules — automatically deciding when to draw from solar panels, battery storage, or the municipal grid.

**AIO 2026 · STEAM Center · Eco Innovation**

---

## 🎯 Problem Statement

Households across Palestine and the Arab world using solar energy systems face daily inefficiencies:
- Unpredictable grid outages
- Variable solar production
- Poor battery management
- Rigid rule-based systems that don't adapt to each household's unique patterns

**Result:** Higher electricity costs, premature battery degradation, and unreliable energy supply.

---

## 💡 Solution

A Machine Learning system that:
1. Analyzes one month of historical household energy data
2. Trains personalized models for each home
3. Generates an optimal hourly schedule for energy usage
4. Predicts grid outages 24 hours in advance
5. Maximizes savings while protecting battery lifespan

---

## 🏗️ Project Structure
solar-energy-orchestrator/
├── data/
│   ├── raw/              # Raw energy data files
│   └── processed/        # Cleaned datasets
├── src/                  # Source code & ML models
├── models/               # Trained model files (.pkl)
├── dashboard/            # Streamlit dashboard
├── reports/              # Analysis reports
│   └── figures/          # Generated charts
├── notebooks/            # Jupyter notebooks for EDA
├── presentation/         # Final poster & slides
├── requirements.txt      # Python dependencies
└── README.md

---

## 🤖 ML Pipeline

| Component | Algorithm | Purpose |
|-----------|-----------|---------|
| Solar Forecasting | XGBoost / Random Forest | Predict hourly solar production |
| Consumption Forecasting | XGBoost / Random Forest | Predict hourly consumption |
| Outage Classification | Random Forest Classifier | Estimate grid outage probability |
| Optimization Engine | Rule-based + Linear Programming | Generate optimal energy schedule |

---

## 🚀 Quick Start

### Prerequisites
- Python 3.10+
- pip

### Installation

```bash
# Clone the repository
git clone https://github.com/mahmoudwaael/solar-energy-orchestrator.git
cd solar-energy-orchestrator

# Install dependencies
pip install -r requirements.txt

# Run the dashboard
streamlit run dashboard/app.py
```

Open your browser at `http://localhost:8501`

---

## 📊 Dataset

The system uses real household energy data from Jenin, Palestine, including:
- Hourly consumption (kWh)
- Solar panel production (kWh)
- Grid availability (binary)
- Battery state of charge (%)
- Historical outage patterns

---

## 👥 Team

- **Project Lead & Developers:** Mahmoud Wael & Mahmoud Nazzal
- **Domain Expert Consultant:** Licensed Solar Engineer
- **Institution:** STEAM Center

---



- AIO 2026 Competition
- STEAM Center, Palestine
- Solar engineering expert consultation

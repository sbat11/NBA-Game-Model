# 🏀 NBA Game Winner Predictor

This project is a machine learning model that predicts the winner of an NBA game based on team statistics, recent performance, and matchup history. It aims to provide accurate pre-game predictions using historical data and ML algorithms.

---

## 🤖 Model Overview

- Trained on historical NBA game data
- Uses team-level features like:
  - Win/loss streaks
  - Offensive and defensive ratings
  - Recent head-to-head performance
  - Player injuries (optional)
- Predicts binary outcome: **Home Win** or **Away Win**

---

## 🛠 Tech Stack

- **Python**
- **Pandas / NumPy** for data processing
- **Scikit-learn** for modeling
- **Matplotlib / Seaborn** for visualization
- Optional: XGBoost, LightGBM, or TensorFlow for advanced modeling

---

## 📈 Performance

- Accuracy: ~71% on recent season test set
- Cross-validated with stratified splits
- Confusion matrix and ROC AUC used for evaluation

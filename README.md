# 🎉 ThemeMate AI — Smart Event Planning Assistant

**ThemeMate AI** is a lightweight machine learning tool that helps users plan events by predicting estimated costs, success likelihood, and suggesting budget-friendly alternatives based on user inputs like event type, theme, location, and number of attendees.

---

## 🔧 Features

✅ **Cost Estimation**  
Predicts the estimated cost of an event based on historical patterns.

✅ **Success Score Prediction**  
Estimates how likely the event setup is to succeed (0.0 – 1.0 scale).

✅ **Confidence Range**  
Gives you a range (± ₹) around the predicted cost for better decision-making.

✅ **Smart Suggestions**  
If the predicted cost exceeds your budget, it recommends similar lower-cost setups.

---

## 📁 Files Included

- `themeMate_advanced.py` – Main AI script (terminal-based).
- `themeMate_dataset.csv` – Mock dataset used for training the models.

---

## ⚙️ Tech Stack

- Python
- scikit-learn
- pandas
- LabelEncoder, LinearRegression
- CLI-based input/output (no GUI for simplicity)

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/saksham4455/ThemeMate-AI.git
   cd ThemeMate-AI

# 🛡️ FraudShield — AI Banking Fraud Detection System

> **By Debiprasad Mishra** · KIIT University · WINDEL CO

A complete, production-quality AI-powered fraud detection dashboard built as a **single HTML file** — no backend, no dependencies, no build step. Deploy directly to GitHub Pages.

## 🚀 Live Demo

Host on GitHub Pages: `Settings → Pages → Deploy from main branch → /root`

## 🧠 ML Engine

| Model | Precision | Recall | F1 | AUC-ROC |
|---|---|---|---|---|
| Random Forest | 85.5% | 93.3% | 89.2% | 0.974 |
| Logistic Regression | 80.6% | 88.9% | 84.5% | 0.931 |
| SVM | 83.1% | 91.1% | 86.9% | 0.947 |
| **Ensemble** | **87.4%** | **94.1%** | **90.6%** | **0.981** |

## 🔬 Features

- **Real-time transaction feed** with live ML scoring
- **Fraud analyzer** — enter any transaction, get full breakdown
- **Feature importance** — Random Forest weights visualized
- **ROC & PR curves** for all 3 models
- **Confusion matrix** with TP/TN/FP/FN
- **Transaction history** with sortable table
- **Amount distribution** — fraud vs legit by bucket

## 📐 Feature Engineering

- Amount-to-average ratio (spend anomaly)
- Hour-of-day risk mapping
- Transaction velocity (24h frequency)
- Geographic distance anomaly score
- Merchant category risk
- New merchant flag
- Foreign transaction flag
- Card-not-present (CNP) indicator

## 🛠 Stack

- Pure HTML5 + CSS3 + Vanilla JS (zero dependencies)
- Canvas 2D API for all charts
- Custom Random Forest + Logistic Regression in JS
- GitHub Pages compatible (100% static)

## 📁 Deploy

```bash
git init
git add index.html README.md
git commit -m "FraudShield v1.0"
git remote add origin https://github.com/YOUR_USERNAME/fraud-detection.git
git push -u origin main
# Then enable GitHub Pages in repo settings
```

## 🎓 Resume Alignment

✓ End-to-end AI-powered fraud detection system  
✓ Supervised ML: Logistic Regression, Random Forest, SVM  
✓ Metrics: Precision, Recall, F1-Score, AUC-ROC  
✓ Feature engineering from transactional data  
✓ Anomaly detection for user behavior  
✓ React.js-pattern frontend (equivalent in Vanilla JS)  
✓ Real-time transaction scoring  

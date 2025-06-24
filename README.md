# 🃏 Poker Hand Prediction

This project uses machine learning to predict the type of poker hand a player has, based on their cards. The model classifies each hand into categories such as high card, one pair, two pairs, straight, flush, etc.

## 📌 Features

- 🔍 Predicts poker hand rankings using supervised classification algorithms.
- 📊 Uses a preprocessed dataset of poker hands with labeled outcomes.
- 📈 Trains and evaluates various models to determine the best-performing algorithm.

## 📁 Dataset

The dataset consists of poker hands represented numerically:
- Each card is encoded with **suit** and **rank**.
- There are **10 attributes** per hand (5 cards × 2 features).
- A **target label** indicates the type of hand (from 0 = 'Nothing' to 9 = 'Royal Flush').

## 🧠 Models Used

- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors
- (Others can be added as needed)

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ar-baazaja/pokerhandprediction.git
   cd pokerhandprediction
   pip install -r requirements.txt

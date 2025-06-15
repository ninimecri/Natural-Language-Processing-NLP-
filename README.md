# Natural-Language-Processing-NLP-
This project aims to build a sentiment classification system for movie reviews using multiple NLP techniques and models. It was developed as part of a challenge for *Film Junky Union*, a community for classic film enthusiasts. The objective is to classify IMDB reviews as positive or negative, achieving a minimum F1-score of **0.85**.
---

## ⚙️ Key Features

- **Five different models** ranging from a simple baseline to deep learning with BERT.
- A **single unified function** that allows easy switching between models for training and testing.
- Ability to classify **new custom reviews** using all trained models.
- Modular and reproducible code with clearly separated sections for preprocessing, training, and evaluation.

---

## 🧠 Models Implemented

| Model | Description |
|-------|-------------|
| **Model 0** | Dummy Classifier (Baseline) |
| **Model 1** | NLTK preprocessing + TF-IDF + Logistic Regression |
| **Model 2** | spaCy preprocessing + TF-IDF + Logistic Regression |
| **Model 3** | spaCy preprocessing + TF-IDF + LightGBM Classifier |
| **Model 4** | BERT Transformer (fine-tuned for sentiment classification) |

All models are run using a **custom function**, which encapsulates the full pipeline: preprocessing → vectorization → training → evaluation.

---

## 📥 Dataset

The dataset used consists of movie reviews from IMDB, with labeled sentiment polarity (positive/negative). It is loaded and split into training and test sets during execution.

---
📈 Evaluation
Models are evaluated using standard metrics:

Accuracy

Precision

Recall

F1-score (target ≥ 0.85)

💡 Future Improvements
Hyperparameter optimization (especially for LightGBM and BERT)

Incorporation of more robust datasets

API or web-based deployment using Streamlit or Flask

📚 Dependencies
Python 3.8+

scikit-learn

NLTK

spaCy

LightGBM

Transformers (Hugging Face)

pandas, NumPy, matplotlib

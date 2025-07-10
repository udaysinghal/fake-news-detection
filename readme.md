# 📰 Fake News Detection using BERT and Classical ML Models

This project compares classical machine learning models and a fine-tuned BERT transformer to classify news articles as real or fake. It is based on a dataset of 6,000 labeled news items and includes end-to-end code for training, evaluation, and deployment.

---

## 📁 Folder Structure
```
fake-news-detection/
├── data/
│   └── news.csv                # Dataset file (not uploaded, provide via link or download)
├── bert_model.py               # Fine-tunes and saves BERT model
├── classical_model.py          # Trains and evaluates classical ML models
├── bert-fake-news-model/       # Saved BERT model artifacts (config, tokenizer, weights)
├── requirements.txt            # Python package dependencies
├── .gitignore                  # Files to exclude from GitHub
└── README.md                   # Project overview and instructions
```

## 🔗 Download Trained Model

Due to GitHub size limits, the fine-tuned BERT model (`model.safetensors`) is available [here on Google Drive](https://drive.google.com/file/d/1GTf2dwtJA7oQwfcHK5Kw034fJhGnP9n5/view?usp=sharing).

The input real fake news dataset can be accesses from the link (https://www.kaggle.com/datasets/singhaluday/real-fake-news-dataset)


---

## 🧠 Models Implemented
- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)
- Random Forest
- Passive Aggressive Classifier
- BERT (Bidirectional Encoder Representations from Transformers)

---

## 📦 Requirements
Install dependencies using pip:
```bash
pip install -r requirements.txt
```

---

## 🚀 Usage
### 🔹 Run Classical Models
```bash
python classical_model.py
```

### 🔹 Fine-Tune BERT Model
```bash
python bert_model.py
```

---

## 📊 Results (Accuracy on Test Set)
| Model                | Accuracy (%) |
|---------------------|--------------|
| Logistic Regression | 91.63        |
| Naive Bayes         | 89.27        |
| SVM                 | 92.82        |
| Random Forest       | 91.55        |
| Passive Aggressive  | 92.27        |
| **BERT**            | **97.47**    |

---

## 🧪 Dataset
A CSV file with ~6,000 entries. Each row contains:
- `title` — News headline
- `text` — Full news text or description
- `label` — "FAKE" or "REAL"

**Note:** If you cannot upload the file, you can share the dataset from Kaggle or Google Drive.

---

## 🧾 Author
**Uday Singhal**  
B.Tech CSE, Delhi Technological University

---

## 📬 Contact
For questions or collaboration, reach out via [udayalwayshere@gmail.com](mailto:udayalwayshere@gmail.com)

# 📩 Определение спама

## 📖 Описание
Этот проект посвящен определению спам-сообщений с использованием различных методов машинного обучения. В качестве базовой модели применяется **Naive Bayes**, после чего применяется более сложная архитектура **DistilBERT**.

## 🛠 Стек 
* **Python**
* **Scikit-learn**
* **Hugging Face Transformers**
* **PyTorch**
* **Pandas & NumPy**
* **Matplotlib & Seaborn**
* **NLTK** 

## 📊 Данные
Для обучения моделей использовался датасет [SMS Spam Collection](https://huggingface.co/datasets/ucirvine/sms_spam) от UCI Machine Learning Repository:

## 🚀 **Обучение моделей:**
* **1️⃣ Наивный Байесовский классификатор** (baseline model)
* **2️⃣ DistilBERT**


## 📌 Результаты
* Улучшение **F1-score** для спама на 4% (**0.93** (Naive Bayes) → **0.97** (DistilBERT))
* **Recall**: **+7%** (**0.90** (Naive Bayes) → **0.97**) — DistilBERT пропускает значительно меньше спама.
* **Precision**: **-1%** (**0.98** → **0.99**) — меньше легитимных сообщений помечаются как спам.
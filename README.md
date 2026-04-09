# 🩺 Smart Clinical Diagnosis Assistant (NLP Intent Detector)

An AI-powered Natural Language Processing (NLP) application designed to act as a clinical triage assistant. This project takes natural language patient complaints as input and predicts the most likely medical condition out of 22 different diagnoses using a fine-tuned **DistilBERT** Transformer model.

## 🚀 Features
* **Natural Language Understanding:** Processes conversational patient symptoms (e.g., "I have a terrible headache and my vision is blurry") instead of relying on rigid keyword matching.
* **Transformer Architecture:** Utilizes `distilbert-base-uncased` for highly efficient, state-of-the-art text classification.
* **Robust to Typos:** Semantic embeddings allow the model to correctly diagnose conditions even if the user makes spelling errors.
* **Minimalist Web Interface:** Includes a clean, user-friendly UI built with Gradio for instant predictions.

## 🛠️ Technology Stack
* **Language:** Python
* **Deep Learning Framework:** PyTorch
* **NLP Library:** Hugging Face `transformers` & `datasets`
* **Model:** DistilBERT (Fine-tuned for Sequence Classification)
* **Web Interface:** Gradio
* **Environment:** Google Colab (T4 GPU)

## 📊 Dataset
This project uses the [gretelai/symptom_to_diagnosis](https://huggingface.co/datasets/gretelai/symptom_to_diagnosis) dataset from Hugging Face. 
* **Size:** 1,065 clinical examples (80% Train, 20% Test)
* **Target Classes:** 22 unique medical conditions (e.g., Migraine, Hypertension, Diabetes, Peptic Ulcer Disease).

## ⚙️ Installation & Usage

Since this project leverages Google Colab's free GPU for optimal performance, the easiest way to run it is through the provided Jupyter Notebook.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git)

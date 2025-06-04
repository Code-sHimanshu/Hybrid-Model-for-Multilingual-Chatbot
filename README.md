# Hybrid Model for Multilingual Chatbot

This project builds a hybrid text classification model combining **Sentence Transformers** and **Logistic Regression** to power a multilingual chatbot interface.

## 🔍 Features

- Combines semantic embeddings (SBERT) with a traditional ML classifier (Logistic Regression)
- High performance on multilingual emotion/sentiment classification
- Future-ready chatbot UI with Bootstrap + Flask API integration

## 📁 Project Structure

Hybrid-Model-for-Multilingual-Chatbot/ 
├── sbert_lr_model.pkl # Trained classifier 

├── label_encoder.pkl # Label encoder 

├── hybrid_model_training.ipynb # Model training notebook 

├── README.md 

# Project documentation


## 💡 Model Info

- **Embeddings**: `sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2`
- **Classifier**: Logistic Regression
- **Input**: User queries/messages
- **Output**: Predicted label (emotion/sentiment)

## 🚀 Upcoming

- [ ] Chatbot UI (Bootstrap + Flask)
- [ ] Real-time text + voice chat support
- [ ] Deployment on Render / Vercel

## 📌 How to Use

1. Clone this repository:
```bash
git clone https://github.com/YOUR_USERNAME/Hybrid-Model-for-Multilingual-Chatbot.git



## 💡 Model Info

- **Embeddings**: `sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2`
- **Classifier**: Logistic Regression
- **Input**: User queries/messages
- **Output**: Predicted label (emotion/sentiment)

## 🚀 Upcoming

- [ ] Chatbot UI (Bootstrap + Flask)
- [ ] Real-time text + voice chat support
- [ ] Deployment on Render / Vercel

## 📌 How to Use

1. Clone this repository:
```bash
git clone https://github.com/YOUR_USERNAME/Hybrid-Model-for-Multilingual-Chatbot.git



2. **Push it to GitHub**:
```bash
%cd /kaggle/working/Hybrid-Model-for-Multilingual-Chatbot

!git add README.md
!git commit -m "Add README.md with project overview"
!git push origin main

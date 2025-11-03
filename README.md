# 🧠 CrisisMind: NLP-Driven Mental Health Support System

### 🌸 Research Internship Project — Suvidha Foundation

**CrisisMind** is an AI-powered multilingual chatbot designed to provide real-time mental health support using **Natural Language Processing (NLP)**.  
It helps users communicate in **English**, **Hindi**, and **Gujarati**, offering emotion-aware responses, sentiment recognition, and empathetic guidance for stress, anxiety, and emotional wellness.

---

## 💡 Project Overview

Mental health support is often limited by language barriers and access to professionals.  
**CrisisMind** bridges this gap through an intelligent multilingual chatbot that understands and responds with compassion.

### ✨ Key Features
- 💬 **Multilingual Support:** English, Hindi, and Gujarati  
- 🧠 **Emotion Detection:** Uses NLP models to analyze emotional tone and sentiment  
- 🤖 **AI Chatbot:** Provides supportive, context-aware responses  
- 📊 **Dataset Analysis:** Preprocessed multilingual mental health datasets  
- 🌍 **Real-Time Interaction:** Deployed model for user-friendly conversations  
- 🔍 **Crisis Detection:** Detects stress, anxiety, or emotional distress levels  

---

## 🧰 Tech Stack

| Category | Tools / Libraries |
|-----------|------------------|
| **Programming Language** | Python |
| **Frameworks** | TensorFlow / PyTorch, Hugging Face Transformers |
| **Libraries** | NLTK, spaCy, Scikit-learn, Pandas, NumPy |
| **Interface** | Streamlit / Flask |
| **Languages Supported** | English, Hindi, Gujarati |
| **Visualization** | Matplotlib, Seaborn, WordCloud |
| **Dataset Handling** | CSV, JSON |

---


---

### 📘 Folder Explanation

| Folder | Description |
|--------|--------------|
| **Datasets** | Multilingual datasets used for emotion and crisis detection |
| **Multilingual Chatbot** | Code and interface for the chatbot in English, Hindi, and Gujarati |
| **Summary & Results** | Evaluation metrics, performance tables, and summary reports |
| **Paper Result** | Final formatted results for research or publication |
| **Visualization** | All plots and charts showing model performance |
| **Notebook** | Main Jupyter/Colab notebook containing code and experiments |

---

Would you like me to give you a **matching `.gitignore`** and **`requirements.txt`** (Python + Streamlit + NLP libraries) to upload alongside this? It’ll make your repo perfectly complete and professional.

---

## 🧮 Dataset Summary

The dataset includes multilingual text (English, Hindi, Gujarati) annotated for:
- Emotion category (e.g., joy, sadness, anger, fear, neutral)
- Stress or crisis detection
- Sentiment (positive, negative, neutral)

| Language | # Samples | Source | Type |
|-----------|------------|--------|------|
| English | 5,000 | Publicly Available Mental Health Dataset | Text |
| Hindi | 3,200 | Translated & Crowdsourced | Text |
| Gujarati | 2,800 | Translated & Crowdsourced | Text |

---

## 📈 Model Performance Highlights

| Model | Language | Accuracy | F1-Score |
|--------|-----------|-----------|-----------|
| BERT (base multilingual) | English | 91% | 0.90 |
| IndicBERT | Hindi | 88% | 0.87 |
| IndicBERT | Gujarati | 86% | 0.85 |

---

## 💬 Chatbot Functionality

- Users can select a language (Hindi / English / Gujarati)  
- The model analyzes the emotional tone of the user’s message  
- Generates empathetic responses and suggestions  
- Detects crisis or stress patterns using keyword + sentiment + emotion combination  

Example interaction:

User (Hindi): मैं बहुत उदास महसूस कर रही हूँ।
Bot: मुझे खेद है कि आप ऐसा महसूस कर रही हैं। आप अकेली नहीं हैं। क्या आप इस बारे में और बात करना चाहेंगी?

yaml
Copy code

---

## 🧾 Research Objective

- Develop a **multilingual NLP system** for mental health assistance.  
- Evaluate **emotion recognition and crisis detection** across languages.  
- Build an accessible chatbot that can assist users in real-time.  

---

## 📊 Results and Visualizations

- 📁 `results/result/` → Contains per-language and per-emotion evaluation tables.  
- 📁 `results/summary/` → Contains aggregated accuracy and F1-score summaries.  
- 📁 `results/visualization/` → Contains plots such as:
  - Confusion matrices
  - Emotion detection heatmaps
  - Multilingual performance comparison charts  

---

## 🚀 How to Run

### 🔹 Clone the Repository
```bash
git clone https://github.com/yourusername/CrisisMind-NLP-Mental-Health-Chatbot.git
cd CrisisMind-NLP-Mental-Health-Chatbot
🔹 Install Requirements
bash
Copy code
pip install -r requirements.txt
🔹 Run the Chatbot (Streamlit example)
bash
Copy code
streamlit run app/app.py
Then open the local server link to interact with the chatbot.

🧑‍💻 Author
👩‍💻 Research Intern: Astuti Kumari
🏢 Organization: Suvidha Foundation
📅 Duration: Research Internship Project (2025)

📜 License
This project is open-source and available under the MIT License.

❤️ Acknowledgments
Suvidha Foundation for providing the research opportunity

Open-source NLP communities (Hugging Face, IndicNLP)

Dataset contributors and language annotators

“Technology with empathy — building bridges for better mental health.”

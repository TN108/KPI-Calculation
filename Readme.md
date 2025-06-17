# LLM-Powered Audio Call Analyzer

This project is a comprehensive system for analyzing customer support calls using cutting-edge machine learning models. It features:

- **Automatic Speech Recognition (ASR)** with diarization
- **Speaker Role Classification** (Agent vs Customer)
- **Sentiment Analysis** using CardiffNLP's RoBERTa model
- **Tonal Emotion Analysis** using HuBERT
- **LLM-Powered Evaluation** using Groq and HuggingFace models
- **Contextual Scoring** from a predefined rulebook via FAISS
- **Interactive Gradio Interface**

---

## 🧪 Features

- Supports WhisperX nd Assembly AI for transcription + diarization
- Classifies speakers using LLaMA 3 via Groq
- Sentiment and tonal analysis for each speaker
- Generates visual charts of analysis
- Retrieves relevant rulebook context using FAISS vector search
- Evaluates overall call quality using an LLM

---

## 👩‍💻 Contributors

- **Group 15**
- **M. Annus Shabbir** — `24280015`
- **Eeman Adnan** — `24280022`
- **Talha Nasir** — `24280040`
- **M. Arslan Rafique** — `24280064`
- **Kashaf Gohar** — `24280009`

---

## 🛠️ Run Locally

1. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Application**

   ```bash
   python llm_project.py
   ```

3. **Access the Interface**
   Open your browser and navigate to:
   ```bash
   http://localhost:7860
   ```

**Notes:**
**Unable to deploy on hugging due to memory issues.**
**faiss_vectorstore.py used to generate faiss vectorstore**

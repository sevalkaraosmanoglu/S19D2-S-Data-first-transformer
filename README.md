# HuggingFace Transformers NLP Project

This project demonstrates multiple Natural Language Processing (NLP) tasks using the HuggingFace Transformers library.

Both pipeline-based and manual implementations are included to understand how transformer models work under the hood.

---

## Tasks Covered

### 1. Sentiment Analysis
- Basic sentiment analysis using HuggingFace pipeline
- Fine-tuned Twitter sentiment model comparison
- Analysis of model limitations on informal text

---

### 2. Text Summarization
- Model: sshleifer/distilbart-xsum-12-6
- Summarization of long texts
- Handling context length issues using truncation and chunking

---

### 3. Question Answering (QA)
- Model: roberta-base-squad2
- Context + question based answer extraction
- Manual implementation using logits (no pipeline)

---

### 4. Translation
- English to Spanish translation using Helsinki-NLP OPUS-MT models
- Pipeline vs manual tokenizer comparison

---

### 5. Speech to Text (ASR)
- Model: openai/whisper-tiny
- Audio transcription using transformer models
- Audio preprocessing with librosa

---

## Key Learnings

- Pipelines are useful for quick prototyping but limited in flexibility
- Manual implementation provides deeper understanding of transformer models
- Transformer models have strict context length limits
- Different models are specialized for different NLP tasks
- Preprocessing (tokenization, truncation, resampling) is critical

---

## Libraries Used

- transformers
- torch
- sentencepiece
- sacremoses
- librosa
- ffmpeg

---

## Notes

- All models are loaded from HuggingFace Hub
- No external APIs were used
- Computation was done locally or on Google Colab
- Pipeline issues were resolved using manual model implementations

---

## Project Structure

- transformers_nlp.ipynb
- README.md

---

## Author

Data Science NLP project using HuggingFace Transformers ecosystem.

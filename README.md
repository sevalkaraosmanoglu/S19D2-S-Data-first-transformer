HuggingFace Transformers NLP Project

This project demonstrates multiple Natural Language Processing (NLP) tasks using the HuggingFace Transformers library.
Both pipeline-based and manual model implementations are included to better understand how transformer models work under the hood.

🚀 Tasks Covered
1️⃣ Sentiment Analysis
Basic sentiment analysis using default HuggingFace pipeline
Comparison with fine-tuned Twitter sentiment model
Observation of model limitations on informal language
2️⃣ Text Summarization
Implementation using sshleifer/distilbart-xsum-12-6
Handling long text inputs using truncation and chunking
Understanding context length limitations in transformer models
3️⃣ Question Answering (QA)
Manual implementation using roberta-base-squad2
Context + question → answer extraction
Span-based answer selection using logits
4️⃣ Translation
English → Spanish translation using Helsinki-NLP OPUS-MT models
Comparison of pipeline vs manual tokenization approaches
5️⃣ Speech-to-Text (ASR)
Speech recognition using openai/whisper-tiny
Audio preprocessing with librosa
Manual inference without pipeline
🧠 Key Learnings
HuggingFace pipelines simplify NLP tasks but may fail in complex cases
Manual model usage provides better control and understanding
Transformer models have context length limitations
Different models are specialized for different languages and tasks
Real-world NLP requires preprocessing (chunking, truncation, resampling)
⚙️ Libraries Used
transformers
torch
sentencepiece
librosa
sacremoses
ffmpeg
📌 Notes
All models are downloaded from HuggingFace Hub
No external APIs (e.g., OpenAI API) were used
Computation was performed locally (Colab / local runtime)
Pipeline failures were resolved using manual model implementations


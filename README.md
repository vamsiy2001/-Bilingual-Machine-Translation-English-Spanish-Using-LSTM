# 🔁 Bilingual-Machine-Translation-English-Spanish-Using-LSTM

This project focuses on building a bilingual machine translation system capable of translating between Spanish and English using a sequence-to-sequence (Seq2Seq) architecture powered by Long Short-Term Memory (LSTM) networks.

The model was trained on the Tatoeba dataset consisting of 141,543 parallel sentence pairs. The goal was to address key linguistic challenges such as word order, gendered nouns, verb conjugations, and article usage across the two languages.

🔍 Key Features

- Implemented an LSTM-based encoder-decoder architecture for translation tasks.
- Integrated Multi-Head Attention, Layer Normalization, and L2 Regularization to enhance translation fluency and mitigate overfitting.
- Achieved a ROUGE-1 score of 0.55, indicating strong alignment with reference translations.

🛠️ Tech Stack

- Python, TensorFlow, Keras, NumPy
- NLP Preprocessing: Tokenization, Padding, Sequence Reversal
- Evaluation: ROUGE Score

📌 Highlights

- Tackled sequence modeling challenges such as long-term dependencies using LSTM layers.
- Focused on capturing contextual relationships in bilingual text using attention mechanisms.
- Explored model regularization and normalization techniques for improved stability and generalization.

📁 Dataset

Tatoeba Project – a publicly available collection of parallel corpora for multilingual translation tasks.

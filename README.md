# Zeyad Essam

4th-year Computer and Communication Engineering student at Alexandria University,
specializing in NLP and deep learning. I build end-to-end AI systems — from
fine-tuning transformer models to deploying full-stack applications.

---

## Projects

### MindScan AI — Depression Detection System
Benchmarked 7 models (Logistic Regression → MentalRoBERTa) on 188K samples.
Fine-tuned MentalRoBERTa to **98.92% F1**, deployed via Flask REST API with a
PHQ-9 conversational screener powered by LLaMA 3.3 70B (Groq).  
`PyTorch` `Hugging Face Transformers` `Flask` `Groq API` `HTML/CSS/JS`

---

### Neural Machine Translation — French → English (Seq2Seq)
Implemented a **Transformer encoder-decoder from scratch** (custom multi-head
attention, causal masking, weight tying) and a BiLSTM with Bahdanau attention.
Beam search decoding and BLEU score evaluation for both architectures.  
`PyTorch` `BPE Tokenization` `BLEU`

---

### LLM Fine-Tuning and Alignment (SFT + DPO)
Fine-tuned **Qwen2-1.5B-Instruct** for code generation via Q-LoRA (4-bit NF4),
then applied **Direct Preference Optimization (DPO)** to align model behavior.
All runs logged with Weights & Biases.  
`PyTorch` `PEFT` `TRL` `bitsandbytes` `Weights & Biases`

---

### RAG Document QA Pipeline
End-to-end RAG pipeline: PDF ingestion → recursive chunking → sentence-transformer
embeddings → FAISS retrieval → Groq LLM inference. Evaluated with **RAGAS**
(faithfulness, relevancy, context precision/recall) and traced with **LangSmith**.  
`LangChain (LCEL)` `FAISS` `RAGAS` `LangSmith` `Groq API`

---

### Online Bookstore System
Relational database schema (normalized, CRUD) with a Flask backend supporting
user management, inventory, orders, and transactions.  
`Python` `Flask` `SQL`

---

## Skills

| Area | Technologies |
|---|---|
| ML / DL | PyTorch, Hugging Face Transformers, scikit-learn, NumPy |
| LLM / Alignment | PEFT (LoRA/Q-LoRA), TRL (SFT/DPO), bitsandbytes, W&B |
| NLP / RAG | BERT, RoBERTa, fine-tuning, seq2seq, FAISS, LangChain, RAGAS |
| Backend | Flask, REST APIs, SQL, Groq API |
| Systems | C, C++, Docker, Linux, Git |
| Languages | Python, Java, C/C++, SQL, JavaScript |

---

## Contact

[LinkedIn](https://www.linkedin.com/in/zeyad-essam) · ziadessam979@gmail.com

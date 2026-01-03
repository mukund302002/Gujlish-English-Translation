# When Gujarati Meets English: Toward Robust Translation of Code-Mixed Low-Resourced Indian Language

This repository accompanies our paper accepted at **LM4UC Workshop, AAAI 2026**:

> **When Gujarati Meets English: Toward Robust Translation of Code-Mixed Low-Resourced Indian Language**  
> Mukund Agarwalla*, Himanshu Kumar*, Nishat Afshan Ansari  
> Indian Institute of Information Technology Nagpur  
> (*Equal contribution*)

---

## 📌 Overview

Code-mixing is a pervasive linguistic phenomenon in multilingual societies like India, where speakers frequently combine regional languages with English. While Hindi–English (Hinglish) translation has received substantial attention, **Gujlish (Gujarati–English)** remains largely unexplored due to the lack of high-quality parallel corpora.

This work addresses this gap by:

- Constructing the **first large-scale, general-purpose Gujlish–English parallel corpus** (≈30k sentence pairs)
- Fine-tuning the **NLLB-200 multilingual translation model** for Gujlish → English translation
- Demonstrating significant improvements over strong commercial baselines such as **Google Translate** and **Devnagri**

Both the **dataset** and **fine-tuned model** are publicly released to support future research in low-resource code-mixed NLP.

---

## 🧩 Contributions

### 1. Gujlish–English Parallel Dataset
- ~30,000 sentence pairs
- General-domain coverage (news, factual, conversational-style text)
- Source English sentences sampled from **BPCC (AI4Bharat)**
- Gujlish translations generated using **GPT-4o** with few-shot prompting
- Human validation to ensure naturalness and realistic code-mixing

### 2. Translation Model
- Fine-tuned **NLLB-200** sequence-to-sequence model
- Adapted to Romanized Gujarati and intra-sentential code-mixing
- Establishes the **first strong baseline** for Gujlish → English translation

### 3. Evaluation
- Automatic metrics: **BLEU, ChrF++, COMET**
- Human evaluation for fluency and semantic adequacy
- Benchmarks adapted from **XNLI** and **IN22**
- Outperforms Google Translate and Devnagri by a large margin

---

## 📂 Repository Structure

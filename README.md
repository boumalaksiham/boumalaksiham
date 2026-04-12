# Siham Boumalak

**M.S. Artificial Intelligence · Northeastern University, Khoury College · Expected 2027**

I build end-to-end ML systems — from research and modeling to deployment and observability. My work spans NLP, computer vision, multi-agent LLM systems, and applied data science. Previously at Schneider Electric building production LLM pipelines.

Open to: **AI/ML Engineering · Applied Research · Data Science · Data Analysis** internships and co-ops · F-1 CPT eligible · Boston, MA

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Siham_Boumalak-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/siham-boumalak-11014b210)
[![Portfolio](https://img.shields.io/badge/Portfolio-boumalaksiham.github.io-378ADD?style=flat-square)](https://boumalaksiham.github.io)

---

## What I work on

```
NLP & Text          →  fine-tuning BERT/DistilBERT, NER, text classification, ROUGE evaluation
Computer Vision     →  CNNs, EfficientNet, OpenCV, image quality scoring, facial recognition
LLM Systems         →  multi-agent pipelines, RAG, LLM observability, hallucination detection
Data Science        →  clustering, regression, A/B testing, forecasting, Tableau dashboards
Deep Learning       →  PyTorch, HuggingFace, transfer learning, ablation studies
```

---

## Projects

### NLP & Deep Learning

**[Product Attribute Extractor — NER](https://github.com/boumalaksiham/Product-NER-Attribute-Extraction)**
Fine-tuned DistilBERT token classifier with BIO tagging to extract 9 attribute types (brand, model, color, storage, size, material, network, generation, count) from raw product titles. Handles multi-word entities like "Le Creuset" and "Deep Purple".
`DistilBERT` `BIO Tagging` `seqeval` `HuggingFace` · **F1=1.00 on BRAND · F1=0.86 on STORAGE**

**[Hierarchical Taxonomy Classifier](https://github.com/boumalaksiham/Taxonomy-Classifier-DistilBERT)**
Shared-encoder multi-task architecture — one DistilBERT encoder feeding 3 independent classification heads (5 / 12 / 18 classes) trained simultaneously. Predicts full 3-level category paths from product titles.
`DistilBERT` `PyTorch` `Multi-task Learning` · **100% Level 1 · 81% Level 3 accuracy**

**[Scientific Paper Analysis — 5-Agent NLP System](https://github.com/boumalaksiham/Final-Project-AI)**
Five specialized agents — Summarization (BART), Citation Analysis (NetworkX), Methodology Extractor (spaCy NER), Critical Analysis, Coordinator — analyzing arXiv papers end-to-end. Evaluated with ROUGE and full ablation studies.
`BART` `spaCy` `NetworkX` `HuggingFace` · **+0.31 ROUGE-1 over single-model baseline**

---

### Computer Vision

**[Product Image Quality Scorer](https://github.com/boumalaksiham/Product-Image-Quality-Scorer)**
Two-stage scorer: EfficientNet-B0 (pretrained ImageNet, MSE regression head) + 7 classical CV signals (Laplacian sharpness, Canny edge density, brightness, contrast, colorfulness, resolution, noise). Scores images 1–5 and generates actionable seller feedback.
`EfficientNet-B0` `OpenCV` `torchvision` `PyTorch` · **Correct ranking on all test images**

**[Nexus-AI — Facial Recognition Attendance System](https://github.com/boumalaksiham/Nexus-AI-Attendance)**
Real-time multi-agent attendance system using dlib HOG + 128D face embeddings. Three dashboards (Admin, Professor, Student), AI-generated absence reports via OpenAI API. B.A. senior thesis.
`OpenCV` `dlib` `Flask` `OpenAI API` · **Departmental Honors · Zero manual tracking**

**[Arabic Handwriting CNN](https://github.com/boumalaksiham/Arabic-Handwriting-CNN)**
CNN trained from scratch on 13,440 labeled images across all 28 Arabic characters. Data augmentation, dropout regularization, confusion matrix analysis on character pairs with highest confusion.
`PyTorch` `CNN` `Data Augmentation` · **92.4% test accuracy**

---

### LLM Systems & Observability

**[AI Guardian — LLM Observability Platform](https://github.com/boumalaksiham/AI-Guardian)**
Production-grade monitoring for LLM applications. Python SDK (`@track_llm_call`) captures latency, token usage, cost, quality scores, and hallucination risk without changing application code. Threshold-based alerting, RAG pipeline tracing, live React dashboard via WebSockets.
`FastAPI` `PostgreSQL` `React` `Python SDK` `LangChain` · **Works with any LLM provider**

---

### ML & Data Science

**[Entity Resolution — Product Matching](https://github.com/boumalaksiham/Entity-Resolution-Product-Matching-Pipeline)**
Two-stage pipeline combining semantic similarity (Sentence Transformers) with an Attribute Guard layer that detects model code, storage, and size conflicts and penalizes the score multiplicatively.
`Sentence Transformers` `PyTorch` `scikit-learn` · **78% → 92%+ accuracy**

**Energy Infrastructure Forecasting** *(Preflet, 2022)*
Analyzed 10+ datasets to forecast transmission line performance and detect anomalies. Compared Random Forest, XGBoost, and regression baselines; XGBoost reached F1=0.84 on imbalanced anomaly detection. Built OpenCV prototype classifying tower types (87% accuracy).
`XGBoost` `Random Forest` `OpenCV` `Python`

**Product Launch Strategy** *(CaffeBerry.co, 2024)*
Integrated 10+ datasets (sales, sentiment, pricing, seasonality); applied clustering for customer segmentation and regression for price elasticity modeling. A/B tested pricing tiers. One product variant greenlit based on analysis output.
`Python` `R` `Tableau` `A/B Testing` `Clustering`

---

## Stack

| Area | Tools |
|---|---|
| NLP & Deep Learning | BERT · DistilBERT · Sentence Transformers · HuggingFace · PyTorch · BIO Tagging · seqeval · BART · spaCy |
| Computer Vision | EfficientNet · ResNet · OpenCV · Laplacian · Canny · torchvision · dlib · CNNs |
| ML & Data Science | scikit-learn · XGBoost · Random Forest · Pandas · NumPy · Tableau · R · A/B Testing · ROUGE |
| LLM & Agents | LangChain · AutoGen · LlamaIndex · OpenAI API · RAG · Prompt Engineering · GPT-4 |
| Infrastructure | FastAPI · PostgreSQL · React · Flask · Python · SQL · Git · Linux |
| Languages | English (fluent) · French (fluent) · Arabic (native) |

---

## Education & Experience

| | |
|---|---|
| 2025 – 2027 | **M.S. Artificial Intelligence** — Northeastern University, Khoury College · ML concentration |
| Summer 2024 | **Data Scientist & Research Assistant** — Schneider Electric · Built multi-agent LLM pipelines (AutoGen, LangChain, LlamaIndex) with GPT-4, Claude, Gemini · Evaluated frameworks across accuracy, latency, cost · Findings delivered to AI leadership |
| Spring 2024 | **Business Analyst** — CaffeBerry.co · Data-backed product launch strategy · Tableau dashboards · A/B testing |
| Summer 2023 | **Web Developer & Research Assistant** — Vivi Dynamics · AI tool evaluation study published in technical report |
| Summer 2022 | **Data Analyst** — Preflet · ML forecasting models · Computer vision prototype |
| 2021 – 2025 | **B.A. Computer Science & Data Science** — The College of Wooster · Departmental Honors |

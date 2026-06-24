# CA-HalluBERT

A Context-Aware Hybrid Transformer Framework for Detecting 
Hallucinations in Generative AI Responses Using Local Knowledge 
Bases — A Case Study of Ghanaian Higher Education (KNUST)

## Overview
CA-HalluBERT is a novel hallucination detection framework 
engineered by fusing a domain-adapted BERT encoder with a 
locally constructed KNUST knowledge graph. A fabricated 
Cross-Attention Alignment Module (CAAM) computes alignment 
scores between AI-generated responses and verified KNUST 
institutional knowledge entries to classify responses as:
- Hallucinated
- Partially Hallucinated
- Factually Grounded

## Engineering Contribution
- Operation: Fabricate (F)
- Module: Cross-Attention Alignment Module (CAAM)
- Base model: bert-base-uncased
- Engineered variant: CA-HalluBERT

## Dataset
- Public: TruthfulQA + HaluEval (pre-training)
- Local: KNUST-HalluSet (fine-tuning + evaluation)

## Computing Environment
- Primary: Google Colab (T4 GPU)
- Backup: Kaggle Notebooks
- Random seed: 42

## Target Journals
- Expert Systems With Applications (ESWA) — Q1
- Knowledge-Based Systems (KBS) — Q1
- Information Processing & Management (IP&M) — Q1

## Supervisor
Rev. Dr. Kwame Ofosuhene Peasah
Department of Computer Science
KNUST, Kumasi, Ghana

## Citation
To be updated upon publication.

## License
MIT License

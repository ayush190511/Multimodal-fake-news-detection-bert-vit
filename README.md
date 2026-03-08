# Multimodal Fake News Detection using BERT and Vision Transformers

This repository contains the research work presented at the
International Conference on Intelligent Computing, Cognitive Networks,
and Smart Systems (IC2NS2 2026).

The work proposes a unified multimodal fake news detection framework
that combines textual and visual representations using transformer-based
architectures.

The model integrates:

• BERT + BiGRU for textual feature extraction  
• Vision Transformer (ViT-B/16) for visual understanding  
• Feature concatenation for multimodal fusion  

The system is evaluated on the Fakeddit dataset and achieves
approximately 90.18% classification accuracy.

---

## Paper

Title:
A Unified Multimodal Framework for Fake News Detection Using BERT and Vision Transformers

Authors:
Ayush Mishra, Naveen Kumar

Conference:
International Conference on Intelligent Computing, Cognitive Networks, and Smart Systems (IC2NS2 2026)

Institution:
Sardar Vallabhbhai National Institute of Technology (SVNIT), Surat

---

## Architecture
Text Input → BERT → BiGRU → Text Features
Image Input → Vision Transformer (ViT-B/16) → Visual Features

Text Features + Visual Features
        ↓
Feature Concatenation
        ↓
Fully Connected Layer
        ↓
Fake / Real Classification

---

## Dataset: Fakeddit

Fakeddit is a large-scale multimodal dataset containing
textual and visual information for fake news detection tasks.

---

## Results

Accuracy: 90.18%
Precision: 0.90
Recall: 0.90
F1 Score: 0.90

---

## Tech Used
Python
PyTorch
HuggingFace Transformers
Vision Transformer (ViT)
BERT
BiGRU
Multimodal Learning

---

## Conference Presentation

This paper was presented at IC2NS2 2026.

![Conference Certificate](images/certificate.png)

---

## LinkedIn Announcement

https://www.linkedin.com/posts/ayush190511_machinelearning-datascience-multimodalai-activity-7426841200848113664-4lDd

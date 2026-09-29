# Faseeh (فصيح) — Arabic Text Readability Classification & Simplification

Introduction

Much of the written Arabic content available today is too complex for a large group of readers, including school students, non-native speakers, and people with reading difficulties. Faseeh addresses this by combining two NLP tasks in one pipeline:

1- Readability classification — predicts how difficult an Arabic sentence is (levels 1–4).

2- Text simplification — rewrites a sentence so it is easier to understand.

Arabic text → Readability Classifier → Text Simplifier → Simplified text

The goal is to give students, educators, and general readers a tool that can assess and reduce the linguistic complexity of Arabic text.


Technologies Used

-Language: Python 3

-Environment: Google Colab (Jupyter notebooks)

-Classical ML: scikit-learn (TF-IDF, SVM, Random Forest, Decision Tree, XGBoost)

-Deep Learning: MSE Regression, Weighted Cross-Entropy, CORAL

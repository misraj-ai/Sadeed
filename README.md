# Sadeed: Advancing Arabic Diacritization

This repository contains evaluation code and benchmark data for Sadeed, a state-of-the-art model for Arabic text diacritization based on a fine-tuned decoder-only language model.

## Overview

Sadeed achieves remarkable performance in Arabic diacritization with a 2.4% WER and 1.2% DER. The model is adapted from Kuwain 1.5B, a compact language model specifically designed for Arabic.

This repository includes:
- Evaluation code for benchmarking diacritization models
- SadeedDiac-25: A comprehensive benchmark spanning both Classical Arabic (CA) and Modern Standard Arabic (MSA)

## SadeedDiac-25 Benchmark

SadeedDiac-25 is a novel benchmark designed to address limitations in existing Arabic diacritization evaluation datasets. It features:
- 1,200 paragraphs (40-50 words each)
- Balanced representation: 50% MSA and 50% CA
- Expert-reviewed diacritization
- Diverse content spanning various domains (sports, politics, religion, culinary arts, etc.)

## Datasets

🤗 you can download the cleaned version of Tashkela [Clean Tashkela Dataset](https://huggingface.co/datasets/ARBML/clean-tashkela)

🤗 you can Download SadeedDiac-25 on huggingface [SadeedDiac-25 Benchmark](https://huggingface.co/datasets/ARBML/SadeedDiac-25)

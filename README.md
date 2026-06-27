# Transformer-Based Image Captioning (BLIP Model)

An academic Computer Vision and Natural Language Processing (Vision-Language) project focused on image caption generation using the BLIP (Bootstrapping Language-Image Pre-training) Transformer model. The project includes data preprocessing, exploratory analysis, fine-tuning, hyperparameter experimentation, and quantitative evaluation using BLEU metrics.

---

## Overview

This project explores automatic image captioning using the BLIP Transformer architecture. Starting from a pretrained BLIP model, the project fine-tunes the model on a subset of the COCO Captions dataset to improve caption generation performance.

The implementation covers the complete deep learning workflow, including dataset preparation, exploratory data analysis (EDA), model fine-tuning, learning rate sensitivity analysis, and performance evaluation.

---

## Objectives

- Utilize a pretrained BLIP Transformer model for image caption generation.
- Fine-tune the model on the COCO Captions dataset.
- Analyze the dataset through visualization and statistical exploration.
- Evaluate caption quality using multi-reference BLEU scores.
- Investigate the impact of different learning rates on model performance.

---

## Features

- BLIP (Bootstrapping Language-Image Pre-training) Model
- Transfer Learning & Fine-Tuning
- COCO Captions Dataset Processing
- Image Preprocessing Pipeline
- Caption Tokenization
- Custom PyTorch Dataset & DataLoader
- Exploratory Data Analysis (EDA)
- Learning Rate Sensitivity Study
- Baseline vs Fine-Tuned Model Comparison
- Automatic Caption Generation
- Multi-Reference BLEU Evaluation
- Performance Visualization

---

## Model Pipeline

The implemented workflow consists of:

1. Dataset Loading
2. Image Preprocessing
3. Caption Extraction
4. Data Splitting (Train / Validation / Test)
5. BLIP Processor
6. Pretrained BLIP Model
7. Fine-Tuning
8. Caption Generation
9. Quantitative Evaluation

---

## Dataset

The project utilizes a subset of the Microsoft COCO Captions dataset.

Dataset characteristics include:

- Images with multiple human-written captions
- Train / Validation / Test split
- Multiple reference captions per image
- Random caption sampling during training

---

## Exploratory Data Analysis

The notebook includes several analyses and visualizations, including:

- Caption Length Distribution
- Most Frequent Words
- Sample Images with Captions
- Caption Length Statistics
- Dataset Split Balance Analysis

These analyses provide insight into the dataset before model training.

---

## Technologies

- Python
- PyTorch
- Hugging Face Transformers
- BLIP (Salesforce)
- Hugging Face Datasets
- NumPy
- Pandas
- Matplotlib
- Pillow (PIL)
- Scikit-learn
- NLTK

---

## Evaluation Metrics

The generated captions are evaluated using:

- BLEU-1
- BLEU-2
- BLEU-3
- BLEU-4

Evaluation is performed using multiple reference captions for each image to obtain a more reliable assessment of caption quality.

---

## Experiments

This project includes several experimental studies:

### Baseline Evaluation

Evaluate the pretrained BLIP model without additional training.

### Fine-Tuning

Fine-tune the BLIP model on the training dataset.

### Learning Rate Sensitivity Analysis

Compare multiple learning rates to determine the optimal configuration for fine-tuning.

### Model Comparison

Analyze the performance difference between the pretrained and fine-tuned models using BLEU scores.

---
## Learning Outcomes

This project demonstrates practical experience in:

- Vision-Language Models (VLMs)
- Transformer Architectures
- Image Caption Generation
- Transfer Learning
- Fine-Tuning Foundation Models
- Deep Learning for Computer Vision
- Natural Language Generation (NLG)
- Hyperparameter Optimization
- Model Evaluation
- Experimental Analysis

---

## Future Improvements

- Fine-tune on the full COCO Captions dataset.
- Evaluate using additional metrics such as CIDEr, ROUGE-L, METEOR, and SPICE.
- Experiment with larger BLIP variants (BLIP-2).
- Integrate beam search and nucleus sampling for caption generation.
- Compare BLIP with alternative image captioning architectures.

---

## License

This repository was developed for educational and academic purposes.

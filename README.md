# Sentiment Analysis using Support Vector Machine (SVM)

## Introduction  
This project focuses on building a **binary sentiment classification model** for Indonesian text data. The dataset consists of **TikTok comments** discussing the progress of Indonesia's capital city. Each comment is labeled as **positive** or **negative** using **XLM-RoBERTa**.  

## Methodology  
- **Word Embedding:** IndoBERT-p1  
- **Classification Algorithm:** Support Vector Machine (SVM)  
- **Hyperparameter Tuning:** Grid Search  

## Best Model & Performance  
The best model was achieved with the following **SVM hyperparameters**:  
- `C`: **100**  
- `degree`: **4**  
- `gamma`: **0.001**  
- `kernel`: **poly**  

This model achieved an **accuracy of 85%** on the test data.  

# AI-Based Clinical Deterioration Prediction System

**Note:** GitHub may occasionally fail to render large Jupyter notebooks and display a preview error. If the notebook preview does not load, please download the notebook and open it using Jupyter Notebook, Google Colab, or VS Code.

## Project Overview

This project presents a three-generation deep learning framework for predicting clinical deterioration and sepsis using physiological patient data.

### Generation 1 — DNN Baseline

This section implements a Deep Neural Network (DNN) using engineered clinical features and compares the performance of SGD and Adam optimizers.

**Includes:**

* Feature Engineering
* SMOTE for Class Balancing
* SGD vs Adam Comparison
* Confusion Matrix
* Accuracy, Precision, Recall, and F1-Score Evaluation

### Generation 2 — Sequential Modeling

This section captures temporal patient information using recurrent neural networks.

**Models:**

* LSTM
* GRU
* Bidirectional LSTM (BiLSTM)

**Includes:**

* Sequential Window Generation
* Transfer Learning with Pretrained Weights
* Performance Comparison
* Training Time Analysis

### Generation 3 — ClinicalBERT

This section applies transformer-based learning using Bio_ClinicalBERT for clinical deterioration prediction.

**Includes:**

* Clinical Note Generation
* Frozen vs Full Fine-Tuning
* Attention Visualization
* Important Clinical Term Analysis
* Per-Class Performance Evaluation

Download and run:

```text
DL_Assignment.ipynb
```


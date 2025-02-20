# Deep Learning Models for Classification, Regression, and Image Classification

This repository contains three Google Colab notebooks demonstrating deep learning solutions for:

1. **Classification** – A deep learning model to solve a classification problem.
2. **Regression** – A deep learning model to solve a regression problem.
3. **Image Classification** – A convolutional neural network (CNN) model to classify images.

Each notebook is integrated with **Weights & Biases** (preferred) or **TensorFlow TensorBoard** to track metrics, visualize training progress, and conduct error analysis.

## Contents
- [Notebooks](#notebooks)
- [Artifacts and Outputs](#artifacts-and-outputs)
- [Evaluation Metrics](#evaluation-metrics)
- [Model Diagrams and Summaries](#model-diagrams-and-summaries)
- [Video Walkthrough](#video-walkthrough)
- [How to Run](#how-to-run)

## Notebooks
| Notebook | Description |
|----------|-------------|
| [Classification](link-to-colab) | Deep learning model for a classification problem. |
| [Regression](link-to-colab) | Deep learning model for a regression problem. |
| [Image Classification](link-to-colab) | CNN model for image classification. |

## Artifacts and Outputs
Each notebook includes the following outputs and visualizations:

- **Accuracy, Precision, Recall, F1-Score (Per Class & Overall)**
- **ROC and Precision-Recall Curves**
- **Per-Class Examples**
- **Per-Class Error Analysis**
- **Training and Validation Loss/Accuracy Curves**
- **Model Summaries and Diagrams**

## Evaluation Metrics
| Metric | Description |
|--------|-------------|
| Accuracy | Overall prediction accuracy. |
| Precision | Class-specific precision scores. |
| Recall | Class-specific recall scores. |
| F1-Score | Harmonic mean of precision and recall. |
| ROC Curve | Receiver Operating Characteristic curve. |
| PR Curve | Precision-Recall curve. |
| Error Analysis | Examples of correct and incorrect predictions per class. |

## Model Diagrams and Summaries
Each notebook includes:
- Model summary using `model.summary()`.
- Model architecture visualization using `plot_model()`.

## Video Walkthrough
A short video walkthrough explaining the code, evaluation metrics, and error analysis is included:
- [Video Link](link-to-video)

## How to Run
1. Clone the repository.
2. Open each Colab notebook using the provided links.
3. Run the cells sequentially.
4. Follow instructions to log into **Weights & Biases** or **TensorBoard** if needed.

## Requirements
- Python 3.x
- TensorFlow
- Keras
- Weights & Biases (`wandb`)

## Notes
- Reference Colabs and slide decks from class were used as inspiration.
- Ensure that all outputs are preserved when saving and uploading notebooks.


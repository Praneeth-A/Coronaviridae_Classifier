# BiLSTM Virus Classifier

This project implements a Bidirectional LSTM (BiLSTM) deep learning model for classifying virus genome sequences. The workflow includes data extraction from NCBI, preprocessing, model training, evaluation, mutation analysis, and model explainability.

## Project Structure

```
MainBI.ipynb
Project_Report.pdf
Result.png
```

- **MainBI.ipynb**: Main Jupyter notebook containing all code for data extraction, preprocessing, model building, training, evaluation, mutation analysis, and explainability.
- **Project_Report.pdf**: Detailed project report.
- **Result.png**: Example output/result visualization.

## Features

- **Data Extraction**: Fetches viral genome data from NCBI using Biopython.
- **Preprocessing**: Encodes DNA sequences numerically for deep learning.
- **Model Training**: Trains a BiLSTM model using TensorFlow/Keras with mixed precision and GPU acceleration.
- **Evaluation**: Evaluates model performance with accuracy, confusion matrix, and classification report.
- **Mutation Analysis**: Detects mutation-prone positions in viral genomes without a reference genome.
- **Explainability**: Identifies which nucleotide positions most influenced the model's prediction for a given input.

## Requirements

- Python 3.x
- Jupyter Notebook
- TensorFlow
- scikit-learn
- numpy
- Bio (Biopython)
- matplotlib
- seaborn

Install dependencies with:

```sh
pip install tensorflow scikit-learn numpy Bio matplotlib seaborn
```

## Usage

1. **Open** MainBI.ipynb in Jupyter Notebook or Google Colab.
2. **Run all cells** sequentially:
    - Data extraction from NCBI (requires internet).
    - Data preprocessing and encoding.
    - Model definition, training, and evaluation.
    - Mutation analysis and visualization.
    - Model explainability.
3. **Review results** in the notebook outputs and Result.png.

## Model Overview

- **Input**: Encoded DNA sequences (A, C, G, T mapped to integers).
- **Architecture**: Embedding → Bidirectional LSTM layers → Dense layers.
- **Output**: Virus class prediction (multi-class classification).

## Results

- High classification accuracy on test data.
- Confusion matrix and classification report for detailed evaluation.
- Identification of mutation-prone positions for each virus class.
- Model explainability by identifying which nucleotide positions in a given input sequence most influenced the model's prediction. 

## References

- [Biopython Documentation](https://biopython.org/wiki/Documentation)
- [TensorFlow Keras Documentation](https://www.tensorflow.org/api_docs/python/tf/keras)
- NCBI Nucleotide Database

---

For details, see MainBI.ipynb and Project_Report.pdf.
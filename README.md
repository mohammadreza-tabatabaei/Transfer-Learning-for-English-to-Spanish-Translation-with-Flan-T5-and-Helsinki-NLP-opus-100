# Transfer Learning for English to Spanish Translation with Flan-T5 and Helsinki-NLP/opus-100

## Introduction
This project demonstrates the use of transfer learning for English to Spanish translation using the Flan-T5 model. We leverage the Helsinki-NLP/opus-100 dataset for training and evaluation.

## Requirements
To run this project, you need to install the following Python packages:

- transformers
- tensorflow
- datasets
- rouge-score
- nltk
## Dataset
The dataset used in this project is the **Helsinki-NLP/opus-100**, specifically the English-Spanish (en-es) subset. It contains parallel translation pairs in both languages, and is used to train and evaluate the translation model.

## Model
We use the **Flan-T5** model, which is a pre-trained transformer-based model fine-tuned for sequence-to-sequence tasks, such as machine translation.

## Training
In this project, we perform **transfer learning** by fine-tuning the **Flan-T5** model on the English-Spanish translation task. The model is trained using the dataset and evaluated on a test set to calculate translation quality.

## Evaluation
After training the model, we evaluate the translations using the following metrics:

- **ROUGE Score**: Measures the quality of the generated translations based on n-grams.
- **BLEU Score**: Measures the precision of the n-grams in the generated translations compared to reference translations.

## How to Use
1. Clone this repository.
2. Install the required packages.
3. Run the script to fine-tune the **Flan-T5** model and evaluate translations.

## Results
The model achieves competitive translation results, and the **ROUGE** and **BLEU** scores are used to evaluate the quality of the generated translations.


You can install them using pip:

```bash
pip install transformers tensorflow datasets rouge-score nltk



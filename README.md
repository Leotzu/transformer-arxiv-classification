# Finetuning an ArXiv Classifier
This project first trains a transformer from scratch on an arXiv abstract dataset, then finetunes that model on a new dataset that classifies whether any input abstract is AI-related or not.

## Pipeline
1) Download the arXiv dataset from Kaggle: https://www.kaggle.com/datasets/Cornell-University/arxiv
2) Train a model on the arXiv dataset with arxiv_transformer.ipynb
3) Finetune the saved model with finetuned_classifier.ipynb (this is trained on finetune_train.jsonl)


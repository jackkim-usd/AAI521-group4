# AAI521-group4
Group 4 Final Team Project for AAI521 Applied Computer Vision for AI. 

This project is a part of the AAI-521 course in the Applied Artificial Intelligence Program at the University of San Diego (USD). 

The main purpose of this project is to assess the application of computer vision introduced in this course. Team will brainstorm a problem, find a dataset, clean and pre-process it, and perform a computer vision project on the data using Python.

Contributors: Ahmed Salem, Jack Kim, Jacob Edwards

Method(s) Used: Computer Vision

Dataset: https://data.mendeley.com/datasets/tywbtsjrjv/1

Technologies: Python
## ResNet50 Evaluation Notebook

- Added `ResNet50_LeafDisease_Evaluation.ipynb`
- Model accuracy: ~97%
- Macro F1: ~0.96
- Includes confusion matrix, F1 chart, sample images, 

On the 10k / 2k / 2k subset of the augmented 39-class dataset, the ResNet50 model reached validation accuracy 0.9634 (val loss 0.1092) and test accuracy 0.9595 (test loss 0.1241). On the 2,000-image test set, overall accuracy was 0.9580, with macro F1 = 0.9544 and weighted F1 = 0.9585. Added ResNet50_LeafDisease_Subset_Augmented.ipynb to train and evaluate this subset model and generate the associated metrics and plots.

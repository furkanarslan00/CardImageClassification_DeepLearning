# Card Image Classification

This project implements a deep learning pipeline for automated classification of playing card images using a Kaggle dataset. The model is based on ResNet50 and achieves high accuracy in distinguishing card types.

## Project Features

- Data download and preprocessing
- Data augmentation
- Model training and evaluation
- Confusion matrix and classification report
- Single image prediction

## Requirements

- Python 3.7+
- TensorFlow
- Keras
- Pandas
- NumPy
- Matplotlib
- Seaborn
- opendatasets

## Usage

1. Install dependencies:
    ```
    pip install -r requirements.txt
    ```

2. Download the dataset:
    ```python
    import opendatasets as od
    od.download("https://www.kaggle.com/datasets/gpiosenka/cards-image-datasetclassification/data")
    ```

3. Run the notebook `CardsClassification.ipynb` step by step.

## Model

- **Architecture:** ResNet50 (pretrained on ImageNet, fine-tuned)
- **Input size:** 224x224 RGB images
- **Loss:** Categorical Crossentropy
- **Optimizer:** Adamax

## Results

- High accuracy on training, validation, and test sets.
- Confusion matrix and classification report provided in the notebook.

## Example Prediction

You can predict a single card image using the provided `predict_card` function in the notebook.

## Contact

Furkan Arslan
📧 furkan0tr0arslan@gmail.com

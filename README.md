# Ear Recognition Project

## Overview
This project is focused on ear recognition using machine learning techniques. The primary objective is to accurately identify individuals based on their ear features. Two different datasets were utilized in this project, and several methods were employed to enhance the model's performance, including resolving an overfitting issue with the second dataset.

## Datasets

### 1. Dataset 1
The first dataset used in this project is [Dataset 1](https://www.kaggle.com/datasets/omarhatif/datasets-for-ear-detection-and-recognition?select=ear+recognition+datasets). This dataset provided a robust foundation for initial model training and testing.

### 2. Dataset 2
The second dataset is [Dataset 2](https://www.kaggle.com/datasets/coopermini/uerc2023?select=split). While this dataset offered additional data for improving the model, it initially caused overfitting, which led to poor generalization performance on new data. This issue was mitigated through various techniques, including:

- Data augmentation
- Dropout layers
- L2 regularization
- Reducing the model complexity

## Model Performance
After addressing the overfitting issue with the second dataset, the model performance improved significantly. Below is a summary of the key metrics after applying the corrective measures:

- **Accuracy:** XX%
- **Precision:** XX%
- **Recall:** XX%
- **F1 Score:** XX%

## How to Use

### Prerequisites
- Python 3.x
- TensorFlow / PyTorch
- [Any other libraries or tools you used]

### Installation
Clone this repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/ear-recognition.git
cd ear-recognition
pip install -r requirements.txt
```
## Results

The model was evaluated on both datasets, and the following results were obtained:

Dataset 1: Achieved a high level of accuracy with minimal overfitting.
Dataset 2: Initially showed overfitting but was resolved through the techniques mentioned above.
## Contributing

Contributions are welcome! If you have any ideas, bug reports, or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

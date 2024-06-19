# Mushroom-Classificiation
Welcome to the Mushroom Classification Project! This repository provides three distinct classification models to determine whether a mushroom is edible or poisonous. If you're keen to experiment with the dataset yourself, you're in the right place.

## Project Overview

Mushroom identification can be a daunting task, but with the power of machine learning, we can automate the classification process. This project leverages three different models to classify mushrooms based on various features. The dataset used for training and testing the models is also provided for your convenience.

## Models Included

1. **Decision Tree Classifier**  
   A robust and interpretable model that uses tree-like structures to make decisions based on the features of the mushrooms.

2. **Random Forest Classifier**  
   An ensemble method that combines multiple decision trees to improve accuracy and prevent overfitting.

3. **Support Vector Machine (SVM)**  
   A powerful classifier that finds the optimal hyperplane to separate the edible mushrooms from the poisonous ones.

## Dataset

The dataset includes several features of mushrooms, such as cap shape, color, gill size, and more. Each mushroom is labeled as either edible or poisonous. This rich dataset is ideal for training and testing the models.

## Accuracy

The models have been evaluated using the provided dataset, yielding the following accuracy scores:

- **Decision Tree Classifier:** 95%
- **Random Forest Classifier:** 98%
- **Support Vector Machine (SVM):** 97%

These accuracy scores indicate the effectiveness of each model in correctly classifying the mushrooms.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Necessary Python libraries (listed in `requirements.txt`)

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/mushroom-classification.git
   ```
2. Navigate to the project directory:
   ```bash
   cd mushroom-classification
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Run the `mushroom_classification.ipynb` notebook to see the models in action and understand the workflow.

## Future Work

There are several potential avenues for future work to enhance the mushroom classification models:

- **Feature Engineering:** Exploring additional features or deriving new features from the existing dataset to improve model performance.
- **Hyperparameter Tuning:** Conducting a more extensive search for optimal hyperparameters to further boost model accuracy.
- **Deep Learning Models:** Investigating the use of neural networks and deep learning approaches for potentially better performance.
- **Real-time Classification:** Developing a web or mobile application to enable real-time mushroom classification in the field.
- **Cross-Validation:** Implementing more robust cross-validation techniques to ensure the models generalize well to unseen data.

## Results

Each model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score. The results are summarized in the notebook, providing insights into which model performs best for this dataset.

## Contributing

We welcome contributions from the community! If you have any suggestions or improvements, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


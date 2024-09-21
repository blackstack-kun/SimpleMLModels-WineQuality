
# Wine Quality Classification

This repository contains the implementation of several simple machine learning classifiers applied to the Wine Quality dataset. The goal is to predict the quality of wine based on various chemical properties.

## Table of Contents
- [Dataset](#dataset)
- [Classifiers Used](#classifiers-used)
- [Implementation](#implementation)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Dataset
The dataset used for this project is the **Wine Quality dataset**, which can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality). It consists of various chemical properties of wine, along with quality ratings ranging from 1 to 10.

## Classifiers Used
The following classifiers were implemented:
1. Random Forest
2. Support Vector Machine (SVM)
3. Logistic Regression
4. K-Nearest Neighbors (KNN)
5. Decision Tree
6. Naive Bayes

## Implementation
The models were trained and evaluated using Python and popular libraries such as:
- Pandas
- NumPy
- Scikit-learn
- Matplotlib (for visualization)

### Data Preprocessing
- Loaded the dataset and performed necessary data cleaning.
- Split the dataset into training and testing sets.
- Normalized or scaled the features as required.

### Model Training
Each classifier was trained on the training set, and performance was evaluated on the test set using accuracy as the main metric.

## Results
The implementation achieved an accuracy of not more than **66%** across all classifiers. The detailed performance metrics and comparison can be found in the project files.

## Installation
To run the code in this repository, ensure you have Python 3.x installed. You can then install the required packages using pip:

```bash
pip install pandas numpy scikit-learn matplotlib
```

## Usage
To run the project, execute the main script:

```bash
python main.py
```

You may need to adjust file paths or configurations based on your local setup.

## Contributing
Contributions are welcome! If you have suggestions for improvements or enhancements, please create a pull request or open an issue.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize any sections or add more details specific to your project!

# Network Analysis and Classification

This repository contains Python code for analyzing and classifying datasets using Machine Learning techniques. It includes data preprocessing, visualization, and classification using Support Vector Machine (SVM) and Backpropagation neural networks. Two datasets are used: Ring datasets and the Bank Marketing dataset.

## Table of Contents

- [Introduction](#introduction)
- [Datasets](#datasets)
- [Installation](#installation)
- [Usage](#usage)
- [SVM Classification](#svm-classification)
- [Backpropagation Classification](#backpropagation-classification)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project showcases the process of analyzing and classifying datasets using Machine Learning techniques. It demonstrates the use of Python libraries like Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, and more.

## Datasets

The project uses two types of datasets for analysis and classification:

1. **Ring Datasets:**
   - `ring_separable.txt`: Separable ring dataset.
   - `ring_merged.txt`: Merged ring dataset.
   - `ring_test.txt`: Test ring dataset.
   - The datasets are loaded, visualized, and preprocessed for SVM classification.

2. **Bank Marketing Dataset:**
   - `bank-additional-full.csv`: Bank marketing dataset.
   - The dataset is loaded, visualized, preprocessed, and classified using SVM.

## Installation

To run the code locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/4Pranjal/Network-Analysis-and-Classification.git
   cd Network-Analysis-and-Classification
   ```

2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. Place the necessary dataset files in the repository folder.

## Usage

1. Open the Python script `dataset_analysis.py` in your preferred Python environment.
2. Ensure that the required dataset files are in the same folder.
3. Run the script to perform data analysis, preprocessing, and classification.

## SVM Classification

- SVM classification is performed using the Support Vector Machine algorithm.
- Hyperparameter tuning is done using GridSearchCV.
- ROC curve is plotted to evaluate the classification performance.

## Backpropagation Classification

- Backpropagation neural network classification is performed for both Ring datasets and the Bank Marketing dataset.
- The `bp_classification()` function is used for Backpropagation classification.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please create an issue or pull request in this repository.

## License

This project is licensed under the [MIT License](LICENSE).

---
## Credits

This repository is maintained by 4Pranjal. Feel free to use and modify the code for educational and research purposes.

For any questions or suggestions, you can contact me through my GitHub profile: [@4Pranjal](https://github.com/4Pranjal).

Made with ❤️ by [Pranjal Jain](https://github.com/4Pranjal)



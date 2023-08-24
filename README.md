<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">Network Analysis and Classification</h3>
  <p align="center">
    A comprehensive data analysis and SVM classification example.
    <br />
    <a href="https://github.com/4Pranjal/network-analysis-and-classification"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/4Pranjal/network-analysis-and-classification/issues">Report Bug</a>
    ·
    <a href="https://github.com/4Pranjal/network-analysis-and-classification/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Code Explanation](#code-explanation)
* [Contributing](#contributing)
* [License](#license)

<!-- ABOUT THE PROJECT -->
## About The Project

This project demonstrates data analysis and Support Vector Machine (SVM) classification using Python. It includes loading and preprocessing datasets, performing exploratory data analysis, and applying SVM classification.

### Built With

* [Python](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/)
* [NumPy](https://numpy.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [scikit-learn](https://scikit-learn.org/)

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* Python (>= 3.6)
* Pip (Python package manager)

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/4Pranjal/network-analysis-and-classification.git
   ```
2. Navigate to the repository
   ```sh
   cd network-analysis-and-classification
   ```
3. Install required libraries
   ```sh
   pip install -r requirements.txt
   ```

<!-- CODE EXPLANATION -->
## Code Explanation

The provided code (`analysis_and_classification.py`) performs the following tasks:

1. **Import Necessary Libraries:**
   - Imports `pandas`, `numpy`, `matplotlib.pyplot`, and `seaborn` for data manipulation, numerical operations, data visualization, and statistical data visualization.

2. **Load and Plot Ring Datasets:**
   - Loads ring datasets (`ring_separable`, `ring_merged`, `ring_test`) from text files.
   - Corrects separator to tab ('\t') and inspects data.
   - Calls `plot_dataset` (not provided) to plot ring datasets.

3. **Load and Analyze Bank Marketing Dataset:**
   - Loads bank marketing dataset (`bank_marketing`) from a CSV file.
   - Prints initial rows and target distribution.
   - Plots distribution of categorical features.

4. **Preprocess Data:**
   - Defines `preprocess_data` function to split, normalize, and split data.
   - Preprocesses ring datasets (`ring_separable`, `ring_merged`).

5. **SVM Classification:**
   - Defines `svm_classification` function to perform SVM classification.
   - Uses `GridSearchCV` to find best parameters, predicts, and plots ROC curve.
   - Performs SVM classification for ring datasets.

6. **Preprocess and Classify Bank Marketing Dataset:**
   - Preprocesses bank marketing dataset using `preprocess_bank_data` function.
   - Performs SVM classification for bank marketing dataset.

<!-- CONTRIBUTING -->
## Contributing

Contributions to enhance the functionality or improve the code are welcome. Here's how you can contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your improvements.
4. Open a pull request.

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[product-screenshot]: images/screenshot.png
 

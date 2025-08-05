# ML Binary Classification Model Evaluation

This repository contains a machine learning project that tackles a binary classification problem for the travel company "Trips & Travel.Com". The company's goal is to improve its marketing strategy for a new Wellness Tourism Package by identifying potential customers, thereby reducing marketing costs and improving targeting efficiency.

## Features

- **Data Preprocessing**: Comprehensive handling of raw data including missing value imputation, categorical encoding, and feature scaling.
- **Feature Engineering**: Creation of new features from existing data to improve model performance.
- **Model Training**: A Random Forest Classifier is trained to predict customer behavior.
- **Hyperparameter Tuning**: Optimization of the Random Forest model's parameters to achieve the best possible performance.
- **Model Evaluation**: Thorough evaluation using a variety of metrics, including Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
- **Performance Visualization**: Generation of a ROC-AUC Curve to visually represent the model's performance.

## Tech

This project utilizes the following technologies and libraries:

- **Python**: The core programming language.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Scikit-learn**: The primary library for machine learning, including model building, preprocessing, and evaluation.
- **Matplotlib**: For data visualization.
- **Seaborn**: For creating aesthetically pleasing statistical graphics.
- **Jupyter Notebook**: For interactive development and documentation of the machine learning pipeline.

## Installation

To get this project up and running on your local machine, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/qosain-bukhari/ML-binary-classification-model-evaluation.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd ML-binary-classification-model-evaluation
    ```

3. **Create a virtual environment** (recommended):
    ```bash
    python -m venv venv
    ```

4. **Activate the virtual environment**:
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```

5. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
    *(Note: You may need to generate a `requirements.txt` file from the project's dependencies if it doesn't already exist.)*

## Run Locally

Once you have installed the necessary dependencies, you can run the Jupyter Notebook to follow the analysis and modeling process:

1. **Start Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```

2. **Open the main notebook**:
    - Navigate to and open the notebook file (e.g., `ML_Binary_Classification.ipynb`) to see the full code, analysis, and results.

## Roadmap

- [x] Data Preprocessing and Exploratory Data Analysis (EDA)
- [x] Feature Engineering and Selection
- [x] Model Training with Random Forest
- [x] Hyperparameter Tuning
- [x] Model Evaluation and Performance Reporting
- [ ] Explore other ensemble methods (e.g., Gradient Boosting, XGBoost).
- [ ] Implement techniques to handle class imbalance (e.g., SMOTE).
- [ ] Deploy the final model as a web service.

## Acknowledgements

- **Trips & Travel.Com**: For providing the business problem and dataset.
- **Scikit-learn documentation**: For providing excellent resources and examples.

## Authors

- [@qosain-bukhari](https://github.com/qosain-bukhari) - Initial work

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

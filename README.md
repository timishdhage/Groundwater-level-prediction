# Groundwater Level Prediction Using Machine Learning

This repository contains the files and resources for the dissertation **"Subsurface Water Discovery: Methods for Identification and Quality Analysis"** submitted as part of the MSc Data Science program. The project explores the prediction of groundwater levels using advanced machine learning techniques.

## Table of Contents
- [Project Description](#project-description)
- [Key Features](#key-features)
- [Repository Structure](#repository-structure)
- [How to Use](#how-to-use)
- [Dependencies](#dependencies)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Description
Groundwater is a crucial freshwater resource, particularly in areas like California with limited surface water availability. This project leverages machine learning models such as Long Short-Term Memory (LSTM) networks, Convolutional Neural Networks (CNNs), and Artificial Neural Networks (ANNs) to predict groundwater levels. By integrating hybrid and ensemble models, the project aims to enhance the accuracy and reliability of predictions, supporting sustainable groundwater management.

## Key Features
- Utilizes a large dataset spanning three decades (1992-2022).
- Incorporates state-of-the-art machine learning techniques to model temporal and spatial dependencies.
- Implements data preprocessing techniques such as wavelet transformations and imputation for noise reduction and handling missing values.
- Compares performance across multiple models, including LSTM, CNN, Random Forest, and Gradient Boosting.

## How to Use
### Prerequisites
Ensure you have Python installed along with the required libraries. Use the provided `requirements.txt` file to set up the environment.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Groundwater-Level-Prediction.git
   cd Groundwater-Level-Prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Explore the dataset:
   Navigate to the `data/` folder to access the groundwater level datasets.

4. Run the models:
   ```bash
   python src/model_training.py
   ```
   This will preprocess the data, train models, and generate results.

5. View Results:
   Check the `results/` folder for visualizations and performance metrics of the models.

## Dependencies
The following Python libraries are required:
- `numpy`
- `pandas`
- `scikit-learn`
- `tensorflow`
- `matplotlib`
- `seaborn`

To install all dependencies, use:
```bash
pip install -r requirements.txt
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
Special thanks to Professor Jamie Twycross for invaluable guidance and support throughout the dissertation project. This work also draws on insights from prior research in machine learning and environmental modeling.

# Deep Learning for Commodity Price Prediction

## Overview
This project focuses on the prediction of commodity prices using deep learning models, offering a comprehensive examination and performance analysis of various models on this task. The primary goal is to implement and evaluate the effectiveness of several machine learning and deep learning models in predicting the close prices of commodities based on historical price data.

## Models Evaluated
- **Linear Regression** and **Support Vector Regression (SVR)**: These models serve as baseline machine learning approaches, exploring linear and non-linear relationships in the data, respectively.
- **Long Short-Term Memory (LSTM)**: A deep learning model known for its effectiveness in handling sequential data, providing insights into its capability to capture hidden patterns in commodity price movements.
- **Convolutional Neural Networks (CNN) + LSTM**: A combined approach that leverages CNNs for feature extraction from sequential input data and LSTM for predicting future commodity prices, aiming to improve accuracy by utilizing both spatial and temporal data characteristics.

## Key Findings
- **Performance Evaluation**: The LSTM model showcased superior performance in capturing temporal dependencies compared to traditional machine learning models like Linear Regression and SVR. The analysis indicates that deep learning models, particularly LSTM, are more adept at handling the complex dynamics of commodity price data.
- **Feature Importance**: The study found that adding more indicators (features) does not necessarily improve model performance, highlighting the significance of careful feature selection and engineering in developing predictive models.
- **Model Comparison**: The combined CNN + LSTM model did not outperform the standalone LSTM model under the evaluated conditions. This suggests that while combining models can be a promising approach, optimal parameter tuning and model architecture adjustments are crucial for realizing potential performance gains.

## Data
The dataset used in this project includes historical price data for six different commodities from 2000 to 2022, sourced from Kaggle. The commodities are Gold, Palladium, Nickel, Brent Oil, Natural Gas, and US Wheat. This data forms the basis for all model training, testing, and evaluation.

## Repository Structure
Below is the repository structure outlining the main directories and their contents:

- `Figures/`: Contains visualizations and figures that are referenced in the project.

- `Final Submission/`: Includes the final versions of the project files, such as the final report and the complete code.

- `reading material/`: Provides additional resources, papers, and literature that support the underlying concepts and methods used in the project.

- `Dissertation.docx`: The comprehensive dissertation document detailing the entire project scope, methodology, findings, and conclusions.

- `commodity 2000-2022.csv`: The dataset used for model training and evaluation, containing historical commodity prices.

- `README.md`: The file you're currently reading, which provides an overview and guide to the repository.

- Other directories and files such as proposals, presentations, and links to video material that provide supplementary context and documentation for the project.

## Getting Started
To replicate the study or to build upon the work done in this project, follow the guidelines below:

1. Clone this repository to your machine.
2. Install the required dependencies listed in the `requirements.txt` file (if available).
3. Review the `Final Submission/` directory to understand the final state of the project.

## Future Work
This project opens avenues for further research, particularly in exploring more advanced deep learning architectures, incorporating additional features and data sources, and refining model parameters for enhanced predictive accuracy.

## Acknowledgments
This work was conducted as part of a final year project at the University of Liverpool, under the supervision of Professor Anh Nguyen. Special thanks to all contributors and sources of external datasets and libraries utilized in this project.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

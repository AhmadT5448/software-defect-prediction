# software-defect-prediction
Software Defect Prediction using Python and ML models. The project focuses on predicting software defects by analyzing historical data and code metrics. It employs techniques like data preprocessing, feature selection, and model training LSTM.


# Dataset: NASA PROMISE Repository for Software Defect Prediction
This project utilizes datasets from the NASA PROMISE repository, which contains various datasets for empirical research on software defect prediction. These datasets provide metrics related to software quality and have been widely used in academic studies to predict software defects using machine learning models.

Overview of the Dataset
The specific dataset used in this project is part of the NASA suite, containing information on software modules with key metrics such as:

Lines of Code (LOC): Measures the size of the software module.
McCabe Cyclomatic Complexity: Quantifies the complexity of the module's control flow.
Halstead Metrics: Includes various measurements of software size, difficulty, effort, and time required for understanding and maintaining the code.
Defect Label: Indicates whether the module was identified as defective (1) or non-defective (0).
Datasets Used
The following datasets from the NASA PROMISE repository were used in this project:

[Dataset Name]: [Brief Description of what the dataset represents].
[Dataset Name]: [Brief Description of what the dataset represents].
Each dataset consists of several features (or metrics) calculated from the source code, which are then used to predict whether a software module is prone to defects.

Data Characteristics
Number of instances: [e.g., 2,100 modules]
Number of features: [e.g., 21 metrics + defect label]
Defective modules percentage: [e.g., 10% defective]
Usage in the Project
The dataset was used to train and evaluate machine learning models for defect prediction. The features provided by the dataset were processed and fed into the models to predict whether a software module would likely be defective based on its complexity, size, and other metrics.

For more detailed information on the NASA PROMISE repository, visit PROMISE Repository link "https://github.com/ApoorvaKrisna/NASA-promise-dataset-repository"

# LSTM Model trained on the dataset
I have trained LSTM model on these dataset!!!

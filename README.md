# Sampling Assignment

## Overview
This repository contains the implementation of various sampling techniques, designed as an assignment to explore the practical application of sampling in machine learning. The primary objective is to test the performance of multiple sampling methods on different machine learning models.

## Assignment Requirements
The assignment involves the following steps:
1. **Dataset Preparation**: Download the dataset from the provided link and balance it using techniques discussed in the class.
2. **Sample Creation**: Generate five samples using the sample size detection formula.
3. **Sampling Techniques**: Apply five different sampling techniques (Random OverSampling, SMOTE, Random UnderSampling, Tomek Links, SMOTETomek).
4. **Model Evaluation**: Evaluate the performance of five machine learning models (Logistic Regression, Random Forest, SVM, Decision Tree, K-Nearest Neighbors) using the sampling techniques.
5. **Performance Analysis**: Determine which sampling technique yields the highest accuracy for each model.
6. **Submission**: Document and discuss the results, and upload the solution to GitHub for submission.

## Files
- **`Sampling_Assignment.ipynb`**: Jupyter Notebook implementing the sampling techniques, dataset balancing, and model evaluation.
- **`Creditcard_data.csv`**: Dataset used for the assignment (to be downloaded as per the provided link).
- **`Sampling_Assignment.pdf`**: Assignment instructions, requirements, and performance metrics table.

## Sampling Techniques and Models
The assignment uses five sampling techniques and evaluates them across five machine learning models. The table below summarizes the performance metrics:

| Sampling Technique   | Logistic Regression | Random Forest | SVM      | Decision Tree | K-Nearest Neighbors |
|-----------------------|---------------------|---------------|----------|---------------|----------------------|
| Random OverSampling  | 0.875000            | 0.991379      | 0.732759 | 0.978448      | 0.978448            |
| SMOTE                | 0.913793            | 0.991379      | 0.435345 | 0.982759      | 0.762931            |
| Random UnderSampling | 0.560345            | 0.676724      | 0.935345 | 0.508621      | 0.693966            |
| Tomek Links          | 0.987069            | 0.987069      | 0.987069 | 0.982759      | 0.987069            |
| SMOTETomek           | 0.913793            | 0.991379      | 0.426724 | 0.978448      | 0.732759            |

## Getting Started

### Prerequisites
To run the code, ensure you have the following installed:
- Python 3.8 or later
- pip (Python package manager)

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/harshulxo/Sampling_Assignment.git
   cd Sampling_Assignment
   ```

### Usage
Run the `Sampling_Assignment.ipynb` notebook to:
- Balance the dataset
- Generate samples
- Apply sampling techniques
- Evaluate models
- Analyze results

For a detailed walkthrough, open the notebook in Jupyter:
```bash
jupyter notebook Sampling_Assignment.ipynb
```

## Repository Structure
```
Sampling_Assignment/
├── data/               # Contains input data files
├── Sampling_Assignment.ipynb  # Notebook with implementation
├── Sampling_Assignment.pdf    # Assignment instructions
└── README.md           # Documentation (this file)
```

## Learning Objectives
1. Understand how to balance datasets using sampling techniques.
2. Learn to apply various sampling techniques in machine learning.
3. Analyze the impact of sampling on model accuracy.
4. Document and present findings effectively.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For questions or feedback, please contact:
- **Author**: Harshul
- **GitHub**: [@harshulxo](https://github.com/harshulxo)

# neural-network-challenge-1
Module 18 Challenge



# Student Loan Repayment Prediction with Neural Networks

## Overview

This project aims to predict student loan repayment success using deep neural networks. By analyzing various features such as payment history, GPA ranking, and alumni success, the model predicts the likelihood of a student repaying their loan. The project involves data preprocessing, model development, training, evaluation, and deployment.

## Files

- **student_loans_with_deep_learning.ipynb**: Jupyter Notebook containing the Python code for the project.
- **student-loans.csv**: Dataset containing information about previous student loan recipients.

## Dependencies

The project requires the following dependencies:

- Python 3
- TensorFlow
- Pandas
- Scikit-learn

Install the dependencies using pip:

```bash
pip install tensorflow pandas scikit-learn
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/neural-network-challenge-1.git
```

2. Open the `student_loans_with_deep_learning.ipynb` notebook in a Jupyter environment.

3. Follow the instructions in the notebook to execute the code cells sequentially.

## Data

The dataset (`student-loans.csv`) contains the following columns:

- payment_history
- location_parameter
- stem_degree_score
- gpa_ranking
- alumni_success
- study_major_code
- time_to_completion
- finance_workshop_score
- cohort_ranking
- total_loan_score
- financial_aid_score
- credit_ranking (target variable)

## Model

The neural network model consists of multiple layers with ReLU activation functions. It is compiled using the binary_crossentropy loss function, the adam optimizer, and accuracy as the evaluation metric.

## Results

After training the model, it achieved an accuracy of approximately 74% on the test dataset. The classification report provides additional insights into the model's performance.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


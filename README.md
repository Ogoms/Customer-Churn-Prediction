# Customer-Churn-Prediction

This project focuses on analyzing customer churn using machine learning techniques. It includes data preprocessing, exploratory data analysis, feature selection, and model training.

## Contributors

https://github.com/Ogoms



## Setup

### Prerequisites

- Python 3.7+
- Virtual Environment

### Installation

1. Clone the repository:

git clone https://github.com/Ogoms/Customer-Churn-Prediction.git
cd customer-churn-analysis


2. Create and activate a virtual environment:

python -m venv virtual
source venv/bin/activate # On Windows use venv\Scripts\activate


3. Install the required packages:

pip install -r requirements.txt


## Usage

1. Set up your database credentials in a `.env` file:

SERVER_NAME=your_server
DATABASE_NAME=your_database
LOGIN=your_login
PASSWORD=your_password


2. Run the main script:

python main.ipynb


## Data

- Training data is imported from an SQL Server database using pyodbc.
- Evaluation and testing data is imported from a local CSV file.

## Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature selection and engineering
- Model training and evaluation
- Hyperparameter tuning

## Models Used

- Random Forest Classifier
- Logistic Regression
- Decision Tree Classifier
- K-Nearest Neighbors Classifier
- Support Vector Machine (SVM)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Packages Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy
- statsmodels
- imbalanced-learn
- pyodbc
- python-dotenv



## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgements



# Customer Churn Prediction

## Objective
The objective of this assignment is to build a predictive model to identify customers at high risk of churn for a telecom company based on synthetically generated customer data.

## Project Structure
The project directory is structured as follows:

## Files Description

- **[`customer_data.csv`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Farnav.STEALTH%2FDocuments%2FThink%20Humble%2Fcustomer_data.csv%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\arnav.STEALTH\Documents\Think Humble\customer_data.csv")**: The dataset containing synthetically generated customer data.
- **[`Customer_Dataset_Generation.ipynb`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Farnav.STEALTH%2FDocuments%2FThink%20Humble%2FCustomer_Dataset_Generation.ipynb%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\arnav.STEALTH\Documents\Think Humble\Customer_Dataset_Generation.ipynb")**: Jupyter notebook used to generate the synthetic customer dataset.
- **[`Model_Training.py`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Farnav.STEALTH%2FDocuments%2FThink%20Humble%2FModel_Training.py%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\arnav.STEALTH\Documents\Think Humble\Model_Training.py")**: Python script containing functions to train various machine learning models.
- **[`Customer_churn_prediction.ipynb`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Farnav.STEALTH%2FDocuments%2FThink%20Humble%2FCustomer_churn_prediction.ipynb%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\arnav.STEALTH\Documents\Think Humble\Customer_churn_prediction.ipynb")**: Jupyter notebook used for exploratory data analysis, model training, and evaluation.
- **[`churn_predictions.csv`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Farnav.STEALTH%2FDocuments%2FThink%20Humble%2Fchurn_predictions.csv%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\arnav.STEALTH\Documents\Think Humble\churn_predictions.csv")**: CSV file containing the predictions of the best model.
- **[`Requirements.txt`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Farnav.STEALTH%2FDocuments%2FThink%20Humble%2FRequirements.txt%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\arnav.STEALTH\Documents\Think Humble\Requirements.txt")**: List of Python packages required to run the project.

## Installation

1. **Clone the repository**:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Create a virtual environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```sh
    pip install -r Requirements.txt
    ```

## Usage

1. **Generate the dataset**:
    Open and run the cells in [`Customer_Dataset_Generation.ipynb`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Farnav.STEALTH%2FDocuments%2FThink%20Humble%2FCustomer_Dataset_Generation.ipynb%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\arnav.STEALTH\Documents\Think Humble\Customer_Dataset_Generation.ipynb") to generate the synthetic customer dataset and save it as [`customer_data.csv`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Farnav.STEALTH%2FDocuments%2FThink%20Humble%2Fcustomer_data.csv%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\arnav.STEALTH\Documents\Think Humble\customer_data.csv").

2. **Train the models**:
    Run the [`Model_Training.py`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Farnav.STEALTH%2FDocuments%2FThink%20Humble%2FModel_Training.py%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\arnav.STEALTH\Documents\Think Humble\Model_Training.py") script to train the Logistic Regression, Random Forest, and Neural Network models. The script will save the trained models and the scaler.

3. **Evaluate the models**:
    Open and run the cells in [`Customer_churn_prediction.ipynb`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Farnav.STEALTH%2FDocuments%2FThink%20Humble%2FCustomer_churn_prediction.ipynb%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\arnav.STEALTH\Documents\Think Humble\Customer_churn_prediction.ipynb") to perform exploratory data analysis, train the models, and evaluate their performance. The notebook will also export the predictions of the best model to [`churn_predictions.csv`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Farnav.STEALTH%2FDocuments%2FThink%20Humble%2Fchurn_predictions.csv%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\arnav.STEALTH\Documents\Think Humble\churn_predictions.csv").

4. **Deploy the models**:
    You can deploy the models as a web app using Flask. Create a file `app.py` and follow the instructions provided in the previous steps to set up the Flask app.

## Model Training Functions

- **`train_logistic_regression(X_train, y_train)`**: Trains a Logistic Regression model.
- **`train_random_forest(X_train, y_train)`**: Trains a Random Forest Classifier model.
- **`train_neural_network(X_train, y_train)`**: Trains a Neural Network model using TensorFlow.

## Evaluation Metrics

The models are evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1-score
- ROC curve
- AUC

## Dependencies

The project requires the following Python packages, as listed in [`Requirements.txt`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Farnav.STEALTH%2FDocuments%2FThink%20Humble%2FRequirements.txt%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\arnav.STEALTH\Documents\Think Humble\Requirements.txt"):
- absl-py==2.1.0
- aiohttp==3.9.5
- aiosignal==1.3.1
- annotated-types==0.7.0
- asttokens==2.4.1
- astunparse==1.6.3
- attrs==23.2.0
- blinker==1.8.2
- Bootstrap-Flask==2.2.0
- boto3==1.34.145
- botocore==1.34.145
- cachetools==5.4.0
- certifi==2024.6.2
- cffi==1.16.0
- charset-normalizer==3.3.2
- click==8.1.7
- colorama==0.4.6
- coloredlogs==15.0.1
- comm==0.2.2
- contourpy==1.2.1
- cycler==0.12.1
- python-dateutil==2.9.0.post0
- python-magic==0.4.27
- pytz==2024.1
- pywin32==306
- PyYAML==6.0.1
- pyzmq==26.0.3
- referencing==0.35.1
- rembg==2.0.57
- requests==2.31.0
- rich==13.8.0
- rpds-py==0.19.1
- rsa==4.9
- s3transfer==0.10.2
- scikit-image==0.24.0
- scikit-learn==1.5.1
- scipy==1.14.1
- seaborn==0.13.2
- selenium==4.22.0
- six==1.16.0
- skipy==0.1.9
- sniffio==1.3.1
- sortedcontainers==2.4.0
- SQLAlchemy==2.0.25
- stack-data==0.6.3
- statsmodels==0.14.2
- sympy==1.13.1
- tenacity==8.4.2
- tensorboard==2.17.1
- tensorboard-data-server==0.7.2
- tensorflow==2.17.0
- tensorflow-intel==2.17.0
- tensorflow-io-gcs-filesystem==0.31.0
- termcolor==2.4.0
- threadpoolctl==3.5.0
- tifffile==2024.7.24
- tornado==6.4.1
- tqdm==4.66.4
- traitlets==5.14.3
- trio==0.25.1
- trio-websocket==0.11.1
- typing_extensions==4.12.2
- tzdata==2024.1
- uritemplate==4.1.1
- urllib3==2.2.2
- uv==0.2.32
- virtualenv==20.26.3
- virtualenvwrapper-win==1.2.7
- wcwidth==0.2.13
- websocket-client==1.8.0
- Werkzeug==3.0.0
- wrapt==1.16.0
- wsproto==1.2.0
- WTForms==3.0.1
- xgboost==2.1.1
- yarl==1.9.4

## License
This project is licensed under the MIT License.

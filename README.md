🎧 Audiobook Conversion Prediction with TensorFlow
This project utilizes machine learning to predict whether a user will purchase an audiobook based on their interaction data. By analyzing user behavior, the model aims to assist in identifying potential buyers, thereby enhancing targeted marketing strategies.​

📂 Project Structure

├── Audiobook_data_train.npz

├── Audiobook_data_validation.npz

├── Audiobook_data_test.npz

├── Audiobooks_data.csv

├── Audiobooks_data_with_labels.csv

├── preprocessing.ipynb

├── ml.ipynb

└── README.md

🧠 Methodology

1. Data Preprocessing (preprocessing.ipynb)
   Loaded and combined datasets from .npz and .csv files.

Handled missing values and normalized features.

Split data into training, validation, and test sets.​
TensorFlow

2. Model Development (ml.ipynb)
   Constructed a neural network using TensorFlow's Keras API.

Implemented early stopping to prevent overfitting.

Achieved an accuracy of approximately 80% on the test set.​
GitHub

📊 Results
Accuracy: ~80% on unseen test data.

Model Architecture: Sequential neural network with dense layers and dropout regularization.

Evaluation Metrics: Accuracy, loss curves, and confusion matrix.​

🛠️ Tools & Technologies
Programming Language: Python

Libraries: TensorFlow, NumPy, Pandas, Matplotlib

Environment: Jupyter Notebook​
coremltools.readme.io

🚀 How to Run
Clone the repository:

`git clone https://github.com/muhammadolammi/buyers_predictor_ml`

`cd audiobook-conversion-prediction`

Install dependencies:

`pip install -r requirements.txt`

Run the notebooks:

preprocessing.ipynb for data preprocessing.

ml.ipynb for model training and evaluation.​

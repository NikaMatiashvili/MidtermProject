# MidtermProject
Simple Machine Learning Project
This is a simple machine learning project that demonstrates a basic workflow for a binary classification task using the Iris dataset.

Project Structure
/MidtermProject
    ├── data/
    │   └── iris.csv
    ├── models/
    ├── src/
    │   ├── init.py
    │   ├── train_model.py
    │   └── predict.py
    ├── requirements.txt
    ├── README.md
    └── main.py

Getting Started

    Clone the repository:

    bash

git clone https://github.com/SWIFTDAWGS/MidtermProject
cd MidtermProject

Install the required dependencies:

bash

    pip install -r requirements.txt

    Download the Iris dataset and save it in the data directory.

Training the Model

To train the machine learning model, run the following command:

bash

python src/train_model.py

The trained model will be saved in the models directory.
Making Predictions

To make predictions using the trained model, run the following command:

bash

python main.py

The predictions for example input data will be displayed.
Project Structure Explanation

    data: Directory to store the dataset.
    models: Directory to store the trained machine learning model.
    src: Directory containing Python scripts for training and prediction.
    requirements.txt: File specifying project dependencies.
    main.py: Script demonstrating how to use the trained model for predictions.

Additional Information

    The machine learning model is a simple Random Forest classifier.
    Example input data for predictions is provided in the main.py script.


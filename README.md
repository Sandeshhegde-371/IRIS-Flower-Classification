# IRIS-Flower-Classification

## Project Overview
This project aims to classify iris flowers into three species using machine learning. It explores different classification models and evaluates their performance to determine the most accurate model.

## Dataset
The dataset used contains the following features:
- **Sepal Length** (cm)
- **Sepal Width** (cm)
- **Petal Length** (cm)
- **Petal Width** (cm)
- **Species** (Target variable)

## Project Structure
```
Iris-Classification/
│── models/                         # Directory to store trained models and encoders
│── iris_classification.py           # Main script for model training and evaluation
│── IRIS.csv                         # Dataset file
│── README.md                        # Project documentation
│── requirements.txt                 # Prerequisites
```

## Installation & Setup
### Prerequisites
Ensure you have Python installed (>=3.7). Install required dependencies using:
```bash
pip install -r requirements.txt
```

### Running the Model
To execute the project, run:
```bash
python iris_classification.py
```

## Models Used
The following machine learning models were tested:
1. **Random Forest Classifier**
2. **Support Vector Machine (SVM)**
3. **K-Nearest Neighbors (KNN)**
4. **Logistic Regression**
5. **Gradient Boosting Classifier**

## Evaluation Metrics
Each model was evaluated using:
- **Accuracy Score**
- **Classification Report** (Precision, Recall, F1-score)
- **Confusion Matrix**

## Results & Visualization
The accuracy of each model is displayed using a bar chart. The best-performing model is saved in the `models/` directory.

## Model Deployment
The best model is saved as `best_iris_model.pkl`, along with the scaler and label encoder. These can be used for future predictions.

## Contributing
Feel free to fork this repository and improve the model or add new features.

## License
This project is open-source.


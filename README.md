# Student Performance Prediction Model

This repository contains a student performance prediction model implemented using various machine learning algorithms such as linear regression, XGBoost, and random forest. The project is organized into a structured pipeline with the following components:

## Src Directory

- **data_ingestion.py**: Handles the ingestion of student performance data.
- **data_transformation.py**: Implements data preprocessing and feature engineering techniques.
- **model_trainer.py**: Trains machine learning models using the preprocessed data.

## Notebook Directory

- **student_performance_prediction.ipynb**: Jupyter Notebook file for exploratory data analysis, model training, and evaluation.

## Pipeline File

- **prediction.py**: Makes predictions using the trained models.

## Additional Files

- **exception.py**: Defines custom exceptions for error handling.
- **logger.py**: Implements logging functionality for better tracking and debugging.

## Usage Guide

1. **Data Ingestion**: Use `data_ingestion.py` to fetch and load student performance data.
2. **Data Transformation**: Preprocess and engineer features using `data_transformation.py`.
3. **Model Training**: Train machine learning models with `model_trainer.py`.
4. **Prediction**: Make predictions on new data using `prediction.py`.
5. **Exploratory Data Analysis**: Refer to the Jupyter Notebook in the `Notebook` directory for detailed analysis and visualization.

## Dependencies

- Python 3.x
- Required Python libraries: scikit-learn, XGBoost, pandas, numpy, matplotlib, seaborn

## Setup

1. Clone the repository: `git clone <repository-url>`
2. Install dependencies: `pip install -r requirements.txt`

## Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/new-feature`
3. Make your changes and commit: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature/new-feature`
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Author

Rutvik Deshpande


# Grade Prediction Using Machine Learning

## Overview

This project predicts student grades based on various factors such as attendance, study hours, stress levels, and exam scores using a Decision Tree Regressor. It preprocesses data, encodes categorical variables, scales numerical features, and trains a model for accurate predictions.

## Features

- **Data Preprocessing**: Handles missing values, encodes categorical variables, and scales numerical features.
- **Model Training**: Uses a Decision Tree Regressor to predict student grades.
- **Prediction Functionality**: Accepts new student data and predicts their final grade.
- **Evaluation Metrics**: Computes MAE, MSE, and R² scores for performance analysis.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/grade-prediction.git
   cd grade-prediction
   ```
2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Prepare the dataset and preprocess the data.
2. Train the Decision Tree model.
3. Use the `predict_grade` function to predict grades for new student inputs.
   ```python
   student_input = np.array([[1, 18, 10, 2, 2, 85, 7, 6, 3, 1, 5, 4, 80]])
   predict_grade(student_input)
   ```

## File Structure

- `data/` - Contains the dataset.
- `models/` - Stores trained models.
- `notebooks/` - Jupyter notebooks for exploration.
- `scripts/` - Python scripts for data processing and training.

## Contributing

Pull requests are welcome! Please follow coding standards and document changes.

## License

This project is licensed under the MIT License.


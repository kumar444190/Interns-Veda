# Consignment Pricing Prediction Project

This project aims to predict consignment pricing based on various factors available in the dataset using machine learning models. The implementation follows modular programming principles to ensure safety, testability, maintainability, and portability.

## Features

- Data loading and initial exploration
- Data cleaning and preprocessing
- Model training and evaluation using:
  - Linear Regression
  - Random Forest Regressor
- Feature importance visualization
- Adherence to PEP 8 coding standards

## Project Workflow

1. *Data Loading*:
   - The dataset is loaded and basic insights like missing values and data structure are explored.

2. *Data Cleaning*:
   - Missing values are handled by dropping rows with nulls (can be customized).

3. *Feature Engineering*:
   - Categorical variables are one-hot encoded.
   - Data is split into training and testing sets (80/20 split).

4. *Model Training*:
   - Linear Regression and Random Forest models are trained on the prepared data.

5. *Model Evaluation*:
   - Models are evaluated using metrics such as Mean Squared Error (MSE) and R² Score.

6. *Feature Importance*:
   - For tree-based models, feature importance is plotted to understand key predictors.

## Prerequisites

Ensure the following Python libraries are installed:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install them using pip:

bash
pip install pandas numpy scikit-learn matplotlib seaborn


## Usage

1. Clone this repository and navigate to the project directory.

2. Replace the placeholder in the main() function with the path to your dataset and the target column:

python
main("path/to/dataset.csv", "TargetColumnName")


3. Run the Python script:

bash
python consignment_pricing_solution.py


## File Structure

- consignment_pricing_solution.py: Main Python script containing the project code.
- README.md: Documentation for the project (this file).

## Example Execution

python
main("dataset.csv", "ConsignmentPrice")


## Coding Standards

The project adheres to [PEP 8](https://www.python.org/dev/peps/pep-0008/) standards for Python coding to ensure readability and consistency.

## Notes

- The dataset must be in CSV format.
- Ensure that the target column in the dataset matches the name provided in the main() function.
- Customize data cleaning and preprocessing steps if necessary for specific datasets.

## Future Enhancements

- Implement additional models for comparison.
- Add hyperparameter tuning for model optimization.
- Create a web interface for user interaction.

## License

This project is open-source and available under the MIT License.

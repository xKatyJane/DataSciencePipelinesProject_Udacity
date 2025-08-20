# StyleSense: Fashion Forward Forecasting

This is a project built for the Data Science Pipelines nanodegree at Udacity (https://www.udacity.com/). The aim of the project is to predict whether reviews left by the customers of a clothing retailer (StyleSense) are positive or negative and whether customer would recommend the product. The predictions are based on various factors, such as: the review text and title, customer age, product category, previous positive and negative feedback and product type.

Various data types are handled (numerical, categorical, text), to train a predictive model, and evaluate its performance. This helps StyleSense gain insights into customer satisfaction and improve shopping experiences.

## Getting Started

Follow the instructions below to set up and run the project on your local machine.

### Dependencies

```bash
pip install scikit-learn numpy pandas spacy matplotlib
```

### Installation

Step by step explanation of how to get a dev environment running.

1. Clone the directory.

```bash
git clone https://github.com/xKatyJane/DataSciencePipelinesProject_Udacity
```

2. Install the requirements:

```bash
pip install scikit-learn numpy pandas spacy matplotlib
```

3. Launch Jupyter Notebook:

```bash
Jupyter Lab
```

4. Navigate to the folder where you saved the directory and run it in the Jupyter Lab

## Testing

### Break Down Tests

To run tests, open the notebook and execute the cells related to model evaluation.

Tests run:
- Data Preprocessing Tests: Confirm handling of missing values, and proper processing of numerical, categorical, and text features.
- Pipeline Tests: Validate that the preprocessing + model pipeline runs end-to-end without errors.
- Model Evaluation Tests: Assess model accuracy, precision, recall, and F1-score on the test dataset.
- Hyperparameter Tuning Tests: Ensure grid search or cross-validation improves model performance.

## Built With

* Scikit learn - [Description of item](https://scikit-learn.org/stable/)

## License

[License](LICENSE.txt)

# StyleSense: Fashion Forward Forecasting

This is a project that predicts whether reviews left by the customers of a clothing retailer (StyleSense) are positive or negative and whether customer would recommend the product. The predictionsare based on the review text, age, product category, and other available features.

Various data types are handled (numerical, categorical, text), to train a predictive model, and evaluate its performance. This helps StyleSense gain insights into customer satisfaction and improve shopping experiences.

## Getting Started

Follow the instructions below to set up and run the project on your local machine.


### Dependencies

```bash
pip install scikit-learn numpy pandas spacy matplotlib
```

### Installation

Step by step explanation of how to get a dev environment running.

1. Clone the project repository:

```bash
git clone https://github.com/udacity/dsnd-pipelines-project.git
```

2. Navigate into the repo directory:

```bash
git clone https://github.com/udacity/dsnd-pipelines-project.git
```

3. Install the requirements:

python -m spacy download en_core_web_sm

5. Launch Jupyter Notebook:

```bash
jupyter notebook
```

## Testing

### Break Down Tests

To run tests, open the notebook and execute the cells related to model evaluation.

Tests run:
- Data Preprocessing Tests: Confirm handling of missing values, and proper processing of numerical, categorical, and text features.
- Pipeline Tests: Validate that the preprocessing + model pipeline runs end-to-end without errors.
- Model Evaluation Tests: Assess model accuracy, precision, recall, and F1-score on the test dataset.
- Hyperparameter Tuning Tests: Ensure grid search or cross-validation improves model performance.

## Project Instructions

This section should contain all the student deliverables for this project.

## Built With

* Scikit learn - [Description of item](https://scikit-learn.org/stable/)

## License

[License](LICENSE.txt)

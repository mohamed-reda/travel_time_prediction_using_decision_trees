# Travel Time Prediction with Decision Trees

## Overview

This repository contains Python code for predicting travel time using a Decision Tree Regression model. The model is
trained on historical travel time data, and the repository includes code for feature analysis, visualization of the
decision tree, and exporting the model.

## Contents

1. **Data Loading and Preprocessing**: Reads historical travel time data from an Excel file using the Pandas library and
   prepares it for model training.

2. **Decision Tree Regression Model**: Utilizes scikit-learn's DecisionTreeRegressor to build a predictive model for
   travel time.

3. **Prediction and Feature Importance**: Makes predictions and calculates feature importance using the trained model.

4. **Visualization of Decision Tree**: Generates a visual representation of the Decision Tree using graphviz and
   matplotlib.

5. **Exporting the Decision Tree Image**: Exports the visualized Decision Tree as an image file.

## Dependencies

- pandas
- scikit-learn
- graphviz
- python-graphviz
- pydotplus

## Usage

1. Install the required dependencies using the provided commands in comments.
2. Run the Python script to train the Decision Tree model, make predictions, and visualize the results.

Feel free to explore and adapt the code for your specific use case.



---


to run jupyter:

jupyter notebook

(Use Control-C to stop this server)

----
pip install -r requirements.txt

python -m pip install jupyter

---
memory profile:

@memory_profiler.profile

python -m memory_profiler main.py

---

from line_profiler_pycharm import profile

@profile

python -m line_profiler main.py.lprof > results.txt

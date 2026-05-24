# xAI
Explainable AI final assignment 

# Installation

To run this notebook, you will need the following Python libraries. You can install them using pip:

```bash
pip install shap captum scikit-learn pandas numpy matplotlib seaborn openml
```
If running on google colab (like me), the first cell handles all installations


# Usage
This section explains how to use my project. 

```markdown
1.  **Open the Notebook:** Open the "xAI final.ipynb" file in a Jupyter Notebook environment
2.  **Run All Cells:** Execute all cells in the notebook sequentially from top to bottom
3.  **Explore Results:
    ** The code will perform the following:
    *   Load and preprocess the 'credit-g' dataset
    *   Train a neural network using 10-fold stratified cross-validation
    *   Evaluate the model's performance (Accuracy, ROC AUC)
    *   Generate SHAP and Integrated Gradients (IG) explanations for feature importance
    *   Visualise and compare the feature importances for both xAI methods
    *   Visualise and compare the feature importances of sensitive features for both xAI methods

Follow the comments and markdown explanations within the notebook for a detailed understanding of each step.

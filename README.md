# Weakly Supervided Named-Entity Recognition using Snorkel

This is the repository of named-entity recognition on the MIT Restaurant datatset (https://groups.csail.mit.edu/sls/downloads/restaurant/).
We leverage Snorkel's modeling framework to label the dataset, and for comparison, use a deep learning model.

To run this code, you would first need to install Snorkel. 

## Installation
Snorkel requires Python 3.6 or later. To install Snorkel, we recommend using pip:

**pip install snorkel**

or conda:

**conda install snorkel -c conda-forge**

For running the deep learning model, you would need to install tensorflow as well.

After this, run the code in order as provided in the notebook.

* For LabelModel, run the **Snorkel Weakly supervised NER - Restaurant Dataset** notebook.
* For the deep learning model, run the **Deep_Learning_model_Restaurant_Dataset** notebook.

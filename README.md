# Insurance Customer Churn Analysis
This notebook analyses a dataset containing insurance customer data and whether the given customers canceled contracts with the insurance company. As the task was given to me while applying for a Data Science role for a company, the file itself is under an NDA and, unfortunately, I cannot share it here. However, the rest of the notebook shows the use of scikit-learn pipelines and inclues some practical graphs that can be used to gain more insight into the dataset at hand.

### Notes
This environment uses a nightly build of scikit-learn because the latest release does not include SimpleImputer.get_feature_names_out(), which is needed to get a dataframe back from a pipeline

### Run
- `pipenv install`
- `pipenv shell`
    - `pip install --pre --extra-index https://pypi.anaconda.org/scipy-wheels-nightly/simple scikit-learn` (see https://scikit-learn.org/stable/developers/advanced_installation.html#installing-nightly-builds)
- `pipenv run jupyter notebook`

### TODO
- complete integration of MLFlow
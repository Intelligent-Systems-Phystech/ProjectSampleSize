## SampleSizeEstimation

### Overview

Sample Size Estimation and Model Selection Technique library affords methods for preliminary data analysis and effective dataset size estimation with respect to small data subset.

Key advantages:
* fast data analysis
* for 50 features SampleSizeEstimation requires around 30 examples for accurate prediction
* visualization of hypothetic train error and data features provided

### Usage

Sample size estimation methods are in `code/lib/m_models.py`. Each method takes a dataset with labels `X, y` and returns a dictionary with results of the estimation. Estimated optimal sample size is `m*`. Demonstration of usage of one of the methods can be seen in `Demo.ipynb`. 

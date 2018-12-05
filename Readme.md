# Name 
In class competition for MSBD5001
## Description
This competition is an individual project as a part of the course MSBD 5001 Foudation of Data Analytics. This competition is about modeling the performance of computer programs. The dataset provided describes a few examples of running SGDClassifier in Python. The dataset features contains parameters of SGDClassifier as well as the parameters used to generate the synthetic training data. And the target feature is the training time. The train data given to us containe 400 data samples of running the SGDclassifier and 13 features including the one target feature. The test data containes 100 data samples without the time feature.
## Programming Language and libraries used
Python 3 has used to code for the competition
sklearn 0.20.0
pandas 0.23.4
numpy 1.14.5
tensorflow 1.10.0
## TensorFlow
TensorFlow is an open source software library for high performance numerical computation with strong support for machine learning and deep learning domains.
## Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
# Current release for CPU-only
pip install tensorflow
```
## Usage
```python
import tensorflow as tf
tf.estimator.inputs.pandas_input_fn()# Returns input function that would feed Pandas DataFrame into the model.
tf.feature_column.numeric_column()# Represents real valued or numerical features.
tf.estimator.DNNLinearCombinedRegressor()# An estimator for TensorFlow Linear and DNN joined models for regression.
```
## How to run the code
Running  as ipython notebook with the required files for train and test in the same folder will run the code.
## Author
Reshika, PALANIYAPPAN VELUMANI (20544313)

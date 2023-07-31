# DDS4400-utils
Integrated util package for DS4400

Setting input data framework by calling `utils.ml_utils.set_framework('...')` or by macros. <br />
Reference - [utils/ml_utils/__init__.py](https://github.com/JerryGCDing/DDS4400-utils/blob/main/utils/ml_utils/framework_handler.py)
### Supported input frameworks
NumPy (default) <br />
Pandas

## Features
### [Metrics](https://github.com/JerryGCDing/DDS4400-utils/blob/main/utils/ml_utils/metric.py)
* Mean Squared Error
* Mean Absolute Error
* Confusion Matrix
* Accuracy Sensitivity Specificity Precision F1-Score
* Mean Perceptron Error
* Phi Coefficient
* Cosine Similarity
* Gini Index
* Entropy
### [Optimizers](https://github.com/JerryGCDing/DDS4400-utils/blob/main/utils/ml_utils/optimizer.py)
* Random Step
* Gradient Descent
* Perceptron
### [Statistics](https://github.com/JerryGCDing/DDS4400-utils/blob/main/utils/ml_utils/stats.py)
* Stateful Naive Bayes
### [Text Processing](https://github.com/JerryGCDing/DDS4400-utils/blob/main/utils/ml_utils/text.py)
* Stateful Vectorization
### [Experimental](https://github.com/JerryGCDing/DDS4400-utils/blob/main/utils/ml_utils/experimental.py)
* Stateful KNN
* Decision Tree

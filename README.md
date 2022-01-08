# ML_Notes

# hyperparameter
* parameter of the learning algorithm

# k-fold CV
k-fold cross-validation
* [scikit-learn](https://scikit-learn.org/stable/modules/cross_validation.html)
  * [`sklearn.model_selection.cross_val_score`](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_val_score.html)

# overfitting vs underfitting
* We want to make a model that's able to generalize (training to test) as accurately as possible so that it will perform classification or prediction tasks as it was intended for.

## overfitting
* building a model that fits the training but not test data
* too complex
* cannot perform accurately against unseen data/training data
* can learn noise or irrelevant information within the dataset
* 
## underfitting
* building a model that is too simple to learn the underlying structure of the data

## Solutions
### Overfitting
* Simplify the model (regularization = constrain the model to make it simplier)
* Gather more training data
* Reduce the noise in the training data

### Underfitting
* Select a more powerful model with more parameters
* Better features on the learning algorithm
* Reduce constraints on the model

# References
* [Introduction to Machine Learning with Python](https://www.oreilly.com/library/view/introduction-to-machine/9781449369880/)
* [Overfitting, IBM](https://www.ibm.com/cloud/learn/overfitting)
* [Computational Genomics with R](https://compgenomr.github.io/book/)

<!-- 
undef/next commit
class imbalance
logistic regression
regularization
MFA
-->

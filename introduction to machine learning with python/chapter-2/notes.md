# Ch. 2 - Supervised Learning

## Classification
In classification, the goal is to predict a class label, which is a choice from a predefined list of possibilities.
1. Binary Classification: special case of distinguishing between exactly two classes.
> is the email spam or not - simple yes/no output.
2. Multiclass Classification: classification between more than two classes.
> iris flower - one of the 3 species.

## Regression
In regression tasks, the goal is to predict a continuous number or a floating-point number in programming terms (or real number in mathematical terms).
> Whether a person makes $40,000 or $40,001 a year does not make a tangible difference, even though these are different amounts of money; if our algorithm predicts $39,999 or $40,001 when it should have predicted $40,000, we don’t mind that much.

## Generalization
If a model is able to make accurate predictions on unseen data, we say it is able to generalize from the training set to the test set.  
The goal is to build a model that is able to generalize as accurately as possible.

## Overfitting
Overfitting occurs when you fit a model too closely to the particularities of the training set and obtain a model that works well on the training set but is not able to generalize to new data.
> The larger variety of data points your dataset contains, the more complex a model you can use without overfitting.

## Underfitting
Underfitting occurs when a model is too simple to capture the underlying patterns in the training data and therefore performs poorly on both the training set and new data.
> If your model is too simple compared to the complexity of the data, it will fail to learn the important relationships, leading to high errors even on the training set.
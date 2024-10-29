# Assignment 49
### Machine Learning with Tensorflow
# Titanic🚢


## In this challenge, we ask you to build a predictive model that answers the question: 🛳
```what sorts of people were more likely to survive?```

## I chased these features to train the model:
- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare

## How to Install
Run following commend :
```
pip install -r requirments.txt
```

## How to Run
```
Run Titanic.ipynb file in jupyter notebook
```




**Evaluate Model on Test Dataset**

||Loss|Accuracy|
|---|---|---|
||0.27198103070259094 | 0.9497607946395874
|||

## I wrote a 3 layers model for training with 100 epochs
## Model Accuracies
<img src="Output\Model_Accuracy.png">


## Model Losses
<img src="Output\Model_Loss.png">




## Calculate Precision and Recall

**Confusion_MatrixModel**

<img src="Output\Confusion_MatrixModel_Accuracy.png">

||Precision|Recall|
|---|---|---|
||0.9517241379310345 | 0.9078947368421053
|||


## **Predict Model on Jack and Rose Data**

* Jack `→` Dead(0)

* Rose `→` Alive(1)


# ****Results****

|Algorithm|Accuracy|
|---|---|
|KNN| 0.6698564593301436 |
|Perceptron| 0.7177033492822966 |
|MLP| 0.9497607946395874 |







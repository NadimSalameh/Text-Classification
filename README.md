# Text-Classification
In this project, we will build a text classification model on song lyrics. The task is to predict the artist from a piece of text.


# Text-Classification
In this project, we will build a text classification model on song lyrics. The task is to predict the artist from a piece of text.


## Authors

- [@NadimSalameh](https://github.com/NadimSalameh)


## Display Confusion Matrix

```python
from sklearn.metrics import ConfusionMatrixDisplay

ConfusionMatrixDisplay.from_predictions(y_test, predictions, normalize=None)

```
![App Screenshot](https://github.com/NadimSalameh/Text-Classification/blob/main/Lyrics_Confusion_Matrix.png)

## Technologies and Tools

* python 3.9.7
* Jupyter Notebook
* Kaggle
* Pandas 
* numpy
* Matplotlib
* seaborn
* Sklearn
* web scarping
* Regular Expression
* Parsing HTML
* Bag of Words
* Class Imbalance
* Naive Bayes


# Data Information:

The code for this project is seperated in two files:

* *Data file*: where I collected and created my data.

* *lyrics_Project*: jupyter notebook conatining the code for the prediction.



In this project, you have to create your data.

1) Go to www.lyrics.com

2) Pick two artists to collect their songs and lyrics (I chose Eminem and Rihanna for my project ). Try not to pick artists that have a high simlarity in their songs.

Note: You can find the code for collecting and creating data in *Data/Create lyrics Data*





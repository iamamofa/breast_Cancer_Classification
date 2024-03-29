# Breast-cancer-classification

Breast Cancer Classification using CNN and transfer learning

## Citing

If you find this code useful in your research, please consider citing the blog:

```
@misc{sagarconvolutional,
  Author = {Abhinav Sagar},
  Title = {Convolutional Neural Network for Breast Cancer Classification},
  Year = {2019},
  Journal = {Towards Data Science},
}
```

## IMPORTANT

Absolutely, under NO circumstance, should one ever screen patients using computer vision software trained with this code (or any home made software for that matter). 

Check out the corresponding medium blog post [https://towardsdatascience.com/convolutional-neural-network-for-breast-cancer-classification-52f1213dcc9](https://towardsdatascience.com/convolutional-neural-network-for-breast-cancer-classification-52f1213dcc9).

## Data

The dataset can be downloaded from [here](https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/). This is a binary classification problem. I split the data as shown-

```
dataset train
  benign
   b1.jpg
   b2.jpg
   //
  malignant
   m1.jpg
   m2.jpg
   //  validation
   benign
    b1.jpg
    b2.jpg
    //
   malignant
    m1.jpg
    m2.jpg
    //...
```    

## Environment and tools

1.Colabs/ Jupyter Notebook/VisualStudio Not Book
2. Numpy
3. Pandas
4. Scikit-image
5. Matplotlib
6. Scikit-learn
7. Keras (auto keras)


## Installation

`pip install numpy pandas scikit-image matplotlib scikit-learn keras`

`jupyter notebook`

## Model

![model](images/image6.png)

## Results

### Loss/Accuracy vs Epoch

![loss/accuracy](images/image1.png)

![loss/accuracy](images/image2.png)

### Confusion Matrix

![roc-auc](images/image3.png)

### ROC-AUC curve

![roc-auc](images/image4.png)

### Correct/Incorrect classification samples

![results](images/image5.png)


![results](images/image7.png)

The model is able to reach a validation accuracy of 98.3%, precision 0.65, recall 0.95, f1 score of 0.77 and ROC-AUC as 0.692.






## Support

If you want to support the development of this app, feel free to [sponsor](https://ko-fi.com/justiceoheneamofa) me or [buy me a coffee](https://ko-fi.com/justiceoheneamofa).

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/justiceoheneamofa)

## Copyright

This project has no license. That means you are not allowed to sell or distribute this app.
All rights reserved.
© 2023 Justice O. Amofa


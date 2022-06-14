## Welcome to qbaocaca's GitHub Page

### My latest project was on Image Classification.

### _On this project, I create a custom dataset of 5 male models and conduct a full pytorch training pipeline. I use a pretrained model and transfer learning, as well as do hyper-parameter search to help increase the accuracy._

### Analysis and evaluation are documented here.

### - _Full Pytorch training pipeline on image classification task [ part1 ]_

### - _Full Pytorch training pipeline on image classification task [ part2 ]_

### _Most of my implementations are based off [Aladdin Persson] and [Python Engineer]._

&nbsp;

## In this repository, there are:

### - a main script for training (using the pretrained vgg16 and transfer learning).

### - a script for hyperparameter search.

### - a script for loading the model either for resumed training or for inference.

### - [a trained model] (45% accuracy).

### - some helper functions

### - a dataset

&nbsp;

## Dataset structure

    train/val
    |_________chau_minh_chi
              |_________chau_minh_chi_01.jpg
              |_________chau_minh_chi_02.jpg
              ...
    |_________keita_machida
              |_________keita_machida_01.jpg
              |_________keita_machida_02.jpg
              ...

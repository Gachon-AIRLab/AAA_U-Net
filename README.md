# AAA_U-Net

## train.py

python train_re.py -s=1 -l=0.0001

[s = scale(arge default = 0.5), l = learning rate(arge default = 0.1)]

train.py split train data and test data, and store test data "/dataset/dataset_test.pth"


## predict.py

python predict.py

"test" mode test one image
"eval" mode use "/dataset/dataset_test.pth"


## result

**[average segmentation evaluation]**


|   | value |
|---|---|
| overlab  | 0.73864144   |
| jaccard  | 0.5655101  |
| dice  | 0.68190914  |
| fn  | 0.26135838  |
| fp  | 0.24389796  |

# ShipDetection
Training a Neural Network to detect ships from satellite imagery, dataset used is a kaggle dataset created by rhammell, link: https://www.kaggle.com/rhammell/ships-in-satellite-imagery

## Binary Classification on Ship Image Chips
The notebook ```ShipSet Model Training.ipynb``` trains resnet-18 binary classiferies to classify image chips based on whether a full ship is captured in the image. The models were trained using 5 fold cross validation, and was able to achive a out of fold accuracy of 0.9555. 

![Confusion Matrix](https://github.com/HighSpeeds/ShipDetection/blob/ebfefbe9f3be62dd6a2f9b97e308a49caced9640/ConfusionMatrix.png)

Below are some sample validation images from each fold, with the ground truth labels and predicted labels.
### Fold 1
![Fold 1 Image](https://github.com/HighSpeeds/ShipDetection/blob/main/fold1.png)
### Fold 2
![Fold 2 Image](https://github.com/HighSpeeds/ShipDetection/blob/ebfefbe9f3be62dd6a2f9b97e308a49caced9640/fold2.png)
### Fold 3
![Fold 3 Image](https://github.com/HighSpeeds/ShipDetection/blob/ebfefbe9f3be62dd6a2f9b97e308a49caced9640/fold3.png)
### Fold 4
![Fold 4 Image](https://github.com/HighSpeeds/ShipDetection/blob/main/fold4.png)
### Fold 5
![Fold 5 Image](https://github.com/HighSpeeds/ShipDetection/blob/main/fold5.png)



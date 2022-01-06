# ShipDetection
Training a Neural Network to detect ships from satellite imagery, dataset used is a kaggle dataset created by rhammell, link: https://www.kaggle.com/rhammell/ships-in-satellite-imagery

## Binary Classification on Ship Image Chips
The notebook ```ShipSet Model Training.ipynb``` trains resnet-18 binary classiferies to classify image chips based on whether a full ship is captured in the image. The models were trained using 5 fold cross validation, and was able to achive a out of fold accuracy of 0.96125. Below are some sample validation images from each fold, with the ground truth labels and predicted labels.
### Fold 1
![Fold 1 Image](https://github.com/HighSpeeds/ShipDetection/blob/main/fold2.png)

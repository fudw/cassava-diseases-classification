# cassava-diseases-classification
<br/><br/>

## Cassava Leaf Disease Classification
### Identify the type of disease present on a Cassava Leaf image
Dataset from https://www.kaggle.com/c/cassava-leaf-disease-classification/<br/>
<br/><br/><br/>
### First attempt with ResNet architecture with tensorflow.keras

### 18.07.2021
v02.5 Trained for 2 more epochs with class weight from sklearn to compensate for class imbalance, and 5e-5 LR. val_loss increased from 0.361 to 0.41; val_acc from 0.89 to 0.86<br/>
v02.4 Trained for 2 more epochs with slightly stronger regularisation due to overfitting last time, and 2e-5 LR. val_loss increased from 0.36 to 0.361; val_acc from 0.88 to 0.89<br/>
v02.3 Trained for 5 more epochs with 1e-4 LR. val_loss reduced from 0.41 to 0.36; val_acc from 0.86 to 0.88<br/>
v02.2 Trained for 2 more epochs with 1e-4 LR. val_loss reduced from 0.51 to 0.41; val_acc from 0.85 to 0.86<br/>
v02.1 Adapted "Normalization" layer in base model. val_loss reduced from 1.08 to 1.01; val_acc did not change. Unfroze base model weights and trained 1 epoch with 1e4 learning rate, val_loss: 0.51; val_acc: 0.85<br/>

### 14.07.2021
v01.2 First round of training after loading pre-trained weights; val_loss: 1.08; val_acc: 0.70<br/>
v01.1 Added data augmentation<br/>
v01 Data loading and preprocessing<br/>

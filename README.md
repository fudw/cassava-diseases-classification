# cassava-diseases-classification
<br/><br/>

## Cassava Leaf Disease Classification
### Identify the type of disease present on a Cassava Leaf image
Dataset from https://www.kaggle.com/c/cassava-leaf-disease-classification/<br/>
<br/><br/><br/>
### First attempt with ResNet architecture with tensorflow.keras

### 18.07.2021
v02.1 Adapted "Normalization" layer in base model. val loss reduced from 1.08 to 1.01; val_acc did not change. Unfroze base model weights and trained 1 epoch with 1e4 learning rate, val_loss: 0.51; val_acc: 0.85<br/>

### 14.07.2021
v01.2 First round of training after loading pre-trained weights; val_loss: 1.08; val_acc: 0.70<br/>
v01.1 Added data augmentation<br/>
v01 Data loading and preprocessing<br/>

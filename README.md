# ML-CNN-
An implementation of CNN using the natural scenes dataset. 
Network Architecture:
The model uses a sequential architecture with Conv2D layers followed by MaxPooling2D layers, a Flatten layer, and Dense layers.
Input Shape: (150, 150, 3)
Output Layer: Softmax activation with 6 units for the 6 classes.
Training Settings:
 Optimizer: Adam
 Loss Function: Categorical Crossentropy
 Metrics: Accuracy
 Epochs: 3
 Batch Size: 32
 Data Augmentation: Enabled during training (`ImageDataGenerator` with rescaling, shearing, zooming, and horizontal flipping)
2. Results
Accuracy:
  - Training Accuracy:
    Epoch 1: ~63.03%
    Epoch 2: ~71.95%
    Epoch 3: ~74.38%
  - Validation Accuracy:
    Epoch 1: ~66.23%
    Epoch 2: ~72.83%
    Epoch 3: ~76.40%
  - Test Accuracy: 76.40%

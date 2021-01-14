# SimpsonsClassifier
In this project, pretrained neural networks will be used to classify the Simpsons by pictures.

## Weights for model
```html
https://drive.google.com/file/d/1--sbH-K1JTELEyGuCLo2I-V4U5Z8C93I/view?usp=sharing
  ```
## Data
```html
https://drive.google.com/file/d/1j63I8u1fJKyWkLDRA1vn-7RasgH99Is8/view?usp=sharing
```
________
### On January 14: 
In current files we use pretrained neural network ResNet50 that gives accuracy 0.85. For fitting we use stepLr scheduler, and optimizer AdamW. With unfreezy all layers.
________
### On January 15:
Pretrained resnet50, first 30 epochs i'am train nn on AdamW optimizer, ReduceOnPlateau scheduller, and CrossEntropy loss, f1-score was 0.95.
Than on next 30 epochs i train nn on SGD optimizer and ReduceOnPlateau scheduler with CrossEntropy loss, f1-score came 1.0, on Kaggle 0.99574.

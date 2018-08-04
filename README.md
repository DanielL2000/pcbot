# PC Bot Application
> ### Django Application + Tensorflow/Keras model to determine whether comment was toxic and provide feedback on whether user should post content online
This repo is functionally incomplete

## Installation
TBA

## Model Architecture
> Current model architecture is crude. Maybe in future will implement more diverse word embeddings and RNN+CNN hybrid
Sequential Model
1. Embedding Layer (128 length vector representation)
2. LTSM Layer
3. Max Pooling
5. Dropout Layer
6. Dense Layer
7. Dropout Layer
8. Dense Layer
9. Binary Cross-Entropy Loss

## Training Data
Human-labeled Wikipedia comments from Kaggle.com's Toxic Comment Classification Challenge

# Landmark-Identification
Kaggle Competetion Link: https://www.kaggle.com/competitions/landmark-recognition-challenge/data

Dataset Link: https://www.kaggle.com/datasets/google/google-landmarks-dataset or https://github.com/cvdfoundation/google-landmark

Link to Downlad Training Data: https://s3.amazonaws.com/google-landmark/metadata/train.csv

Steps Followed:
1. Data Preparation
2. Model Selection

2 models have been choose for this pre-training phase, all of them having at least once won the Large Scale Visual Recognition Challenge (ILSVRC) based on the ImageNet database, namely VGG-16 and ResNet

VGG-16 Initial Training:
![initial_vgg16_training](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/599ef516-10a8-4737-8e84-34c1100c1fe9)

ResNet Initial Training:
![initial_resnet_training](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/cc919edb-d0a2-4eff-a504-67825e4eeeea)

Initial Training Results:
![initial_model_results](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/af5abf6e-33f1-4462-84ae-24818a1b674b)
3. Model Finetuning and Optimization
4. Ensembling and Results

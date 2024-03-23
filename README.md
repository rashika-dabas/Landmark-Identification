# Landmark-Identification
Kaggle Competition Link: https://www.kaggle.com/competitions/landmark-recognition-challenge/data

Dataset Link: https://www.kaggle.com/datasets/google/google-landmarks-dataset or https://github.com/cvdfoundation/google-landmark

Link to Download Training Data: https://s3.amazonaws.com/google-landmark/metadata/train.csv

Steps Followed:
1. Data Preparation

![prepared_dataset](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/0e03ef65-d908-49f8-b772-6714006c43f0)

2. Model Selection

2 models have been chosen for this pre-training phase and both of them won at least once the Large Scale Visual Recognition Challenge (ILSVRC) based on the ImageNet database, namely VGG-16 and ResNet.

VGG-16 Initial Training:
![initial_vgg16_training](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/6f9d9ac2-f46a-4e60-b216-456ac036b488)

ResNet Initial Training:
![initial_resnet_training](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/44af936b-2738-447b-bbec-d70fa0459bd2)

Initial Training Results:
![initial_model_results](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/49006564-f0ca-4702-ab76-00fcc1004e05)

3. Model Finetuning and Optimization

Finetuning VGG-16:

![finetuned_vgg16](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/a2220956-5a5c-4f71-90e2-b08437e81ff9)

![finetuned_vgg16_top](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/777e98ae-ea8a-44d5-a7d7-b79d634e87e2)

![finetuned_vgg16_top_training](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/1aedb610-1e7d-469f-b2b9-533b1682fb84)

![finetuned_vgg16_top_training_plots](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/434d741d-5564-46b6-a059-84b845534365)

![finetuned_vgg16_complete](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/e160c5eb-9395-41e9-b8a0-a031d82bfa8c)

Final Testing Accuracy for VGG-16: 72.73%

Finetuning ResNet:

![finetuned_resnet](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/63161388-48b1-459d-8f4e-cd0ab05624c0)

![finetuned_resnet_top_training](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/354a66f8-94b8-41fc-98e5-49f45c95dd6c)

![finetuned_resnet_top_training_plots](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/1062917b-a34d-4671-b75b-25719a23b8ab)

Final Testing Accuracy for ResNet: 63.64%

Link to Access Final Models: https://www.kaggle.com/models/rashikadabas/landmark-identification-models

4. Ensembling and Results

Ensembling Inputs:

![emsembling_inputs](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/bce5d3ef-50b0-4d7d-ac0f-65cc11bb06e0)

Final Testing Accuracy After Ensembling Using Average: 72.73%

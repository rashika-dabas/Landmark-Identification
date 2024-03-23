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

![finetuned_vgg16](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/d444cfa2-f157-45ad-92fd-b2fb8350eeff)

![finetuned_vgg16_top](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/9e342b6d-f4b8-4496-a188-493b7931af8e)

![finetuned_vgg16_top_training](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/1ec7f00c-1ab9-4050-a74a-8e5f8a22c492)

![finetuned_vgg16_top_training_plots](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/2867fcc3-3057-44e4-a150-0428e23fd759)

![finetuned_vgg16_complete](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/6f120750-af3c-41a9-8db9-5aca65a8e829)

Final Testing Accuracy for VGG-16: 90.91%

Finetuning ResNet:

![finetuned_resnet](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/63161388-48b1-459d-8f4e-cd0ab05624c0)

![finetuned_resnet_top_training](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/354a66f8-94b8-41fc-98e5-49f45c95dd6c)

![finetuned_resnet_top_training_plots](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/1062917b-a34d-4671-b75b-25719a23b8ab)

Final Testing Accuracy for ResNet: 63.64%

Link to Access Final Models: https://www.kaggle.com/models/rashikadabas/landmark-identification-models

4. Ensembling and Results

Ensembling Inputs:

![emsembling_inputs](https://github.com/rashika-dabas/Landmark-Identification/assets/77570881/b01f2462-c8ac-43c4-a1a3-fbc6ef0c8c37)

Final Testing Accuracy After Ensembling Using Average: 72.73%

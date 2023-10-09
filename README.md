# Cerebral-Artery-Segmentation-Challenge-MICCAI-SMRA-2023
We got the rank 9 of 21 in Cerebral Artery Segmentation Challenge by MICCAI and SMRA 2023


We used nnU-Net with default configuration such as batch size of 2 and Dice+CE as loss function. The model is trained with 100 public data and tested with 50 unseen images by challenge organizers. 
For more details, please read the report file. 
Our model (UW) got ranked 9 of 21 in Cerebral Artery Segmentation Challenge by MICCAI and SMRA 2023.
Link:
https://codalab.lisn.upsaclay.fr/competitions/9804

Very competitive results. Our model achieved the following results:
SCORE: 0.8801
DSC: 0.8765
DSCstenosis: 0.8999
AHD: 0.8874
AHDstenosis: 0.8482

# Inference

1- Install nnU-Net from the original repository (https://github.com/MIC-DKFZ/nnUNet) , or the code we shared here. </br>
2- Download the trained models via the link: https://drive.google.com/drive/folders/1Fro2-AGPkQBmvlAqmahko-fMv7B21dXb?usp=sharing </br>
3- Copy the test images to "nnUNet_raw_data_base/nnUNet_raw_data/Task101_SCGM/imagesTs" and run the code:</br>
!nnUNet_predict -i nnUNet_raw_data_base/nnUNet_raw_data/Task101_SCGM/imagesTs -o nnUNet_Prediction_Results/Task101_SCGM -t 101 -tr nnUNetTrainerV2 -m 3d_fullres --num_threads_preprocessing 1



You can also find the segmented output of test images via:
https://drive.google.com/drive/folders/1rQRjBqQOo2IEQUjfb6ypQv_g8sw3OdIZ?usp=sharing  *****

Original Image: (Image No.88 from training data)
</br>
![image](https://github.com/orouskhani/Cerebral-Artery-Segmentation-Challenge-MICCAI-SMRA-2023/blob/main/snapshot0002.png)

Predicted Mask by Our Model:
</br>
![image](https://github.com/orouskhani/Cerebral-Artery-Segmentation-Challenge-MICCAI-SMRA-2023/blob/main/snapshot0001.png)

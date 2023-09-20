# Cerebral-Artery-Segmentation-Challenge-MICCAI-SMRA-2023
We got the rank 9 of 21 in Cerebral Artery Segmentation Challenge by MICCAI and SMRA 2023


We used nnU-Net with default configuration such as batch size of 2 and Dice+CE as loss function. The model is trained with 100 public data and tested with 50 unseen images by challenge organizers. 
Our model (UW) got rank 9 of 21 in Cerebral Artery Segmentation Challenge by MICCAI and SMRA 2023.
Link:
https://codalab.lisn.upsaclay.fr/competitions/9804

Very competitive results. Our model achieved the following results:
SCORE: 0.8801
DSC: 0.8765
DSCstenosis: 0.8999
AHD: 0.8874
AHDstenosis: 0.8482

*** Please find the output segmented test images via: 
https://drive.google.com/drive/folders/1-Ph83oPgZAXDB5iKADSZgCjNb6-BP2Hk?usp=drive_link  *****

Original Image: (Image No.88 from training data)
</br>
![image](https://github.com/orouskhani/Cerebral-Artery-Segmentation-Challenge-MICCAI-SMRA-2023/blob/main/snapshot0002.png)

Predicted Mask by Our Model:
</br>
![image](https://github.com/orouskhani/Cerebral-Artery-Segmentation-Challenge-MICCAI-SMRA-2023/blob/main/snapshot0001.png)

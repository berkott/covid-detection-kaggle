# Covid Detection Kaggle
Team ML-Ballers

## Overview
This project is for the SIIM-FISABIO-RSNA COVID-19 Detection competition. The current private score achieved by the model is 0.189.

## Technical Description
We used a two stage approach to locate opacities in chest x-rays and then diagnose the severity of COVID-19. The opacity localzation step is done using a YOLOv5l model pretrained on image net, retrained on given chest x-ray images. Then the diagnosis of COVID-19 is done using a random forest classifier trained on the given data. 


*Notes:* Kaggle notebooks run bash commands following a '!' character. Additionally, some of the directories such as the input directory come from Kaggle.
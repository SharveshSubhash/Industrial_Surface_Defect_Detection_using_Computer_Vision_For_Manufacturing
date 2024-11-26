# Industrial_Surface_Defect_Detection_using_Computer_Vision_For_Manufacturing
This implementation is based on the Research that got published last year called "PatchCore: Industrial Anomaly Defect Detection".
The whole architecture presented in the image attached. The S2, R2 are the results and evaluation report of the model.
Uses a pre-trained CNN based ResNet model for feature extraction based encoding of the images which are then saved in the memory bank while training. This memory bank is used while testing to find out the Anomaly score that is found using a nearest feature vector searching algorithm. Anomaly scores above 1 for a component's image is classified as "Defective" or else, it is classified as "Not Defective".

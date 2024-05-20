# faceImageQualityAssessment---Stochastic embedding robustness face image quality(SER-FIQ)
Here we have given a detailed explaination of our thesis project.
Initially we selected two datasets. One for training and one for testing. Then we deviced six use cases. Pretrained model with dropout regularization, Pretrained model with dropout regularization - on-top model without dropouts, Pretrained model with dropout regularization - on-top model with dropouts, Pretrained model without dropout regularization, Pretrained model without dropout regularization - on-top model without dropouts, Pretrained model without dropout regularization - on-top model with dropouts. Here we selected pretrained models as an ArcFace model trained with dropouts and an OpenFace model trained without dropouts. The architectires of the models are illustrated below. 

Pretrained models were taken from : https://pypi.org/project/deepface/
ArcFace Model : Pretrained model with dropouts
OpenFace model : Pretrained model without dropouts

On-top model with dropouts built on top of the ArcFace model :


![ONTOP-YES-DROPOUTS-ARCFACE](https://github.com/krishnappa90/faceImageQualityAssessment---SERFIQ/assets/169172827/2e33edef-a4a2-4159-97c0-ec525a3a2e79)





On-top model without dropouts built on top of the ArcFace model :


![ONTOP-NO-DROPOUTS-ARCFACE (1)](https://github.com/krishnappa90/faceImageQualityAssessment---SERFIQ/assets/169172827/c3861bef-6043-49c5-b139-1bfc0e24c749)





On-top model with dropouts built on top of the OpenFace model :


![ONTOP-YES-DROPOUTS-openface](https://github.com/krishnappa90/faceImageQualityAssessment---SERFIQ/assets/169172827/7f4fd739-bef0-4d27-936d-0ea00d06e862)

On-top model without dropouts built on top of the OpenFace model :
![ONTOP-no-DROPOUTS-openface](https://github.com/krishnappa90/faceImageQualityAssessment---SERFIQ/assets/169172827/1895e340-ede7-4195-81bb-369fd223712c)

Then we trained the models in each use case. Later the testing was done and a different dataset was validated with an accuracy of 95%. Finally, the SER-FIQ scores were computed for every image in the test dataset. To evaluate the performance of the face recognition system, the error vs reject curves were computed.


Results: It was observed that when the dropout regularization was applied to both the pretrained model and the on-top model, the performance was better than all other use cases. A Full pledged thesis report is attached in this repository, which explains every detail of my masters thesis.



References :




https://arxiv.org/abs/2003.09373




https://github.com/pterhoer/FaceImageQuality

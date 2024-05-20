# faceImageQualityAssessment---SERFIQ
Here we have given a detailed explaination of our thesis project.
Initially we selected two datasets. One for training and one for testing. Then we deviced six use cases. Pretrained model with dropout regularization, Pretrained model with dropout regularization - on-top model without dropouts, Pretrained model with dropout regularization - on-top model with dropouts, Pretrained model without dropout regularization, Pretrained model without dropout regularization - on-top model without dropouts, Pretrained model without dropout regularization - on-top model with dropouts. Here we selected pretrained models as an ArcFace model trained with dropouts and an OpenFace model trained without dropouts. The architectires of the on-top models that were built on the pretrained models are illustrated below. 



Then we trained the models in each use case. Later the testing was done and a different dataset was validated with an accuracy of 95%. Finally, the SER-FIQ scores were computed for every image in the test dataset. To evaluate the performance of the face recognition system, the error vs reject curves were computed.
Results: It was observed that when the dropout regularization was applied to both the pretrained model and the on-top model, the performance was better than all other use cases. A Full pledged thesis report is attached in this repository, which explains every detail of my masters thesis.

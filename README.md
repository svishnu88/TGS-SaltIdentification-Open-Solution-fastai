# TGS-Open-Solution-Fastai

The Solution uses a Unet with ResNet34 as an encoder. The data is split into 5-folds and the model is trained with RandomFlip augmentation. TTA with horizonatal flip and average of the 5 models is used to generate test submissions. To validate the correctness of the solution I ran the training loop with sizes 64,128 and 256 with a cycle lenght of 30 each and it scored on Kaggle - 0.829.

Note: You can check fast.ai lesson 14 where Jeremy Howard an amazing mentor and teacher shows how to solve a similar problem. 

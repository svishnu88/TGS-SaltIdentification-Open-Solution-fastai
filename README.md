# TGS-Open-Solution-Fastai

## Kaggle Score: 0.829

Main Architecture: Unet with ResNet34 encoder. 

Training: 

- RandomFlip augmentation
- Batch sizes: 64, 128, 256 with cycle length = 30

Cross Validation: 

- 5 folds
- Test time augmentation with horizontal flip

Final Submission: 

- Model Averaging of 5 models

Getting Started? 
You can check [fast.ai lesson 14](http://course.fast.ai/lessons/lesson14.html) where Jeremy Howard an amazing mentor and teacher shows how to solve a similar problem. 

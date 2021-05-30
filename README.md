# Facial-Key-Points-Detection-and-Emotion-Classification
- Dataset consists of 15 facial key-points(x,y) of 2140 images and 20k facial images with associated expressions.
- Performed Image Visualization, Augmentation by flipping, changing brightness (3x data increase), Normalization.
- Built 2 Resnet-18 models, one to detect key facial points and another to classify Facial Expression that gave an accuracy of 83% and 87% respectively, and assessed performance using confusion matrix and classification report.
- Combined both models for final predictions and deployed it on TensorFlow serving.

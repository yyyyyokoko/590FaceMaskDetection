# Comparison of Deep Learning Model Performances on Real-Time Face Mask Detection
------------------------------------------------------------------------------------

This project defines and compares three deep learning algorithms trained and tested on Face Mask Dataset, and presents the accuracy as the result. The OpenCV technique is introduced to combine neural network models for real-time face mask detection.

## Members:
[Luwei Lei](https://github.com/yyyyyokoko)

[Julia Zhu](https://github.com/Yihan-Julia-Zhu)

[Yu Xiao](https://github.com/YuniceXiao)

## Final Write-up: `590_final_report.pdf`
The final paper of this project.

## Dataset
[Face Mask Dataset](https://www.kaggle.com/ashishjangra27/face-mask-12k-images-dataset)

## Code for Training Models: 
  - `model_CNN.ipynb`
  - `model_MobileNetV2.ipynb`
  - `model_VGG16.ipynb`
  
These 3 ipynb files contain the code of training the four deep learning models including  CNN-1layer, CNN-4layer, MobileNetV2 and VGG16.

## h5 saved from Models: `model_CNN4.h5`,`model_mobileNet.h5`,`model_vgg16.h5`
After traning each model, we save the model in h5 file, which will be used for the real-time computer vision detection.

## Code for Real-time Testing: `app.py`
To run the detector on a computer with a camera, redefine the "model" by typing the corresponding h5 file name in in line22.



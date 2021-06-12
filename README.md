# ece228project

These repo contains notebooks for the American Sign Language Classification project.

The dataset we used through out the project can be found here:

ASL dataset: https://www.kaggle.com/ahmedkhanak1995/cnn-on-sign-language-gesture-images-dataset

SLGI dataset: https://www.kaggle.com/paultimothymooney/interpret-sign-language-with-deep-learning

pre_trained vgg16 model can be accessed at the Keras Pretrained Model section on the link: https://www.kaggle.com/paultimothymooney/interpret-sign-language-with-deep-learning/data

### Here is a brief introduction on each notebook:

- `CNN_withaugmentation.ipynb` loads the ASL dataset, run data augmentation, create a CNN model, then it train, test, and save the model.
- `CNN_withoutaugmentation.ipynb` loads the ASL dataset, create a CNN model, then it train, test, and save the model.
- `VGG16_ASL_WithFlip.ipynb` utilize ASL dataset from Kaggle, run data augmentation,and separate images into training and testing, create a VGG16 model, then it train, test, and save the model.
- `VGG16_ASL_WithoutFlip.ipynb` utilize ASL dataset from Kaggle, and separate images into training and testing, create a VGG16 model, then it train, test, and save the model.
- `ASL_ResNet.ipynb` uses the ASL dataset with/without data augmentation, and create a ResNet50 model to train, test and save the model.


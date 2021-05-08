# About

![Example](https://camo.githubusercontent.com/f0fe57a3540c293e21dcadff0cf5dedf3aaaea16509613822ee713fd40228a91/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313833382f312a6f4233533579484868766f75674a6b50587563386f672e676966)

This repository has a solution to a classification problem that uses convolutional neural networks to check if in an image there is a dog or a cat.

## Dataset

You can download the compressed dataset at https://www.kaggle.com/c/dogs-vs-cats/data

## Installation

You need to install the following packages

```bash
pip install zipfile38
pip install tensorflow
pip install matplotlib
pip install Pillow==2.2.2
pip install keras
```
# Comparison Of Architectures

To evaluate the data set, training was carried out with 3 convolutional neural network architectures: Xception, ResNet50 and VGG16. The table below shows the accuracy and loss for each model.

Model | #Xception | #ResNet50 | #VGG16 |
--- | --- | --- |  --- |
Accuracy graph | ![Example](https://camo.githubusercontent.com/f0fe57a3540c293e21dcadff0cf5dedf3aaaea16509613822ee713fd40228a91/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313833382f312a6f4233533579484868766f75674a6b50587563386f672e676966) | ![Example](https://camo.githubusercontent.com/f0fe57a3540c293e21dcadff0cf5dedf3aaaea16509613822ee713fd40228a91/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313833382f312a6f4233533579484868766f75674a6b50587563386f672e676966)| ![Example](https://camo.githubusercontent.com/f0fe57a3540c293e21dcadff0cf5dedf3aaaea16509613822ee713fd40228a91/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313833382f312a6f4233533579484868766f75674a6b50587563386f672e676966)|
File| ```CatOrDog_XCEPTION.ipynb``` | ```CatOrDog_RESNET50.ipynb``` |  ```CatOrDog_VGG16 .ipynb``` |

### The best model

The best trained model was the ```VGG16```, its accuracy was superior to the others, as well as its loss was inferior to the others

## Example

An execution of the "CatOrDog.ipynb" file can be used with images of dogs and cats, the image below demonstrating a prediction made during the execution of the code.

![Example](https://github.com/LuizAlencar17/cat-and-dog-recognition/blob/main/Files/example.png?raw=true)



## License

[MIT](https://choosealicense.com/licenses/mit/)
# ![GA Logo](https://camo.githubusercontent.com/6ce15b81c1f06d716d753a61f5db22375fa684da/68747470733a2f2f67612d646173682e73332e616d617a6f6e6177732e636f6d2f70726f64756374696f6e2f6173736574732f6c6f676f2d39663838616536633963333837313639306533333238306663663535376633332e706e67) CNNs: Additional Topics

## Recording
This lesson is intended to be given asynchronously. There are 3 separate videos that need to be watched in consecutive order. You may view the corresponding recordings here:

1. Part I: [Working with Keras datasets](https://youtu.be/33JzGJb1HiY)
1. Part II: [Data Augmentation in Keras](https://www.youtube.com/watch?v=F9a81BGt6Wk)
1. Part III: [Using Pre-trained Models in Keras](https://youtu.be/ya-VZL9PR_0)

## Data and Notes
Because of the size of the data (237.3MB), it is not included in this repository. You can download it separately from Kaggle [here](https://www.kaggle.com/datasets/phucthaiv02/butterfly-image-classification?select=test).

Furthermore, if you're going to be using Google Colab to follow along with this lesson, you'll need to upload this dataset to a folder in your Google Drive first. Then, during the lesson, you'll need to mount your Google Drive to your Colab instance's filesystem. This step is not depicted during the lesson. You can do that like we've done in class with this command:

```python
from google.colab import drive
drive.mount('/content/drive')
```

## Lesson Plan
This lesson is in 3 distinct parts:
* Working with "datasets" in Keras
* Data augmentation of image data using Keras
* Using a pre-trained model to enhance your model fitting using VGG16 in Keras

## Additional Resources
* _Deep Learning with Python, 2nd Ed_ by Francois Chollet. Seriously, get ahold of this book!

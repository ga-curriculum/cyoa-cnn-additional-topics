# <picture><img src="https://ga-curriculum.github.io/universal-resources-internal/ga-logos/ga-red-cog-128x128.png" alt="" height="48" align="absmiddle"></picture> CNNs: Additional Topics

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

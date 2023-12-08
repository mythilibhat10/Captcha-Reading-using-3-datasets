# Captcha-Reading-using-3-datasets

--> Datasets used: 
        1. https://www.kaggle.com/datasets/parsasam/captcha-dataset
        2. https://www.kaggle.com/datasets/electrototo/vulnerable-captchas
        3. https://www.kaggle.com/datasets/ascagne/2characterscaptcha
    
--> Introduction:
A CAPTCHA is a type of challenge–response test used in computing to determine whether the user is human to deter bot attacks and spam. For this CAPTCHA reading project, we needed to develop a training model that can read any type of CAPTCHA provided.

--> Libraries used for the training model:
  1. NumPy: It provides support for arrays, matrices, and mathematical functions. NumPy is used for numerical operations, array manipulation, and data storage, especially in the context of deep learning and data processing.
  2. OpenCV: It provides tools for image and video analysis. OpenCV is used for image loading, manipulation, and preprocessing in this program.
  3. TensorFlow: It is commonly used for building and training neural networks. TensorFlow is used for its Keras API to preprocess images and prepare data for machine learning.
  4. PIL (Pillow) - Python Imaging Library: The Python Imaging Library, often referred to as Pillow, is used for opening, manipulating, and saving image files. Pillow is used here to convert images to arrays for further processing.
  5. os: The os module provides a way of using operating system-dependent functionality, such as reading file paths and directory operations. os is used to list files in directories and construct file paths.
  6. collections: The collections module provides additional data structures that are alternatives to built-in data types such as lists, dictionaries, and tuples.
collections. The counter is used here to count the occurrences of characters in the labels.
  7. Counter: The Counter class is part of the collections module and is used to count the occurrences of elements in a sequence, such as a list or an array. The counter is used to count the occurrence of each character in the labels.

--> The objective of this project:
  The primary objective of the code is to prepare image data for training machine learning models, specifically for tasks where the input data consists of images containing multiple characters. This includes tasks like optical character recognition (OCR), where the goal is to recognize and interpret characters within images.

--> Scope of this project:
  1. Image Data Preprocessing: The code is primarily focused on preprocessing image data. It prepares images for use in machine learning models by applying a series of image processing techniques.
  2. Handling Multiple Labels: The code is designed to handle images where each image contains multiple labels (characters). These characters may range from 5 to 10 alphanumeric characters.
  3. Batch Processing: The code efficiently processes images from multiple folders in batches. This is useful for handling large datasets.
  4. Data Normalization: After processing, the code normalizes the pixel values in the images, which is a common preprocessing step in machine learning. It scales the pixel values to the range [0, 1].
  5. Character Occurrence Count: The code calculates and prints the occurrence count of each character across all the images in the training dataset.




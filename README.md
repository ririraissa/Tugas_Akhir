
# Development of a Color Mapping and Classification System for Batik Textile from Garut and Solo

Batik cloth is one of the cultural legacies that has its own distinct characteristics in terms of pattern selection, variety, ornamentation, and colors according to its region of origin.

As time goes by, the distinctive features of batik cloth have started to fade, giving rise to modern batik.

Until now, to understand the unique characteristics of batik fabric patterns, color mapping has still been done manually.

# Dataset
110 Batik textile's images with 55 Batik Garutan and 55 Batik Solo

# Objective
Detecting colors in batik fabric images automatically and predict its origin based on batik textile's extracted color coordinate by using:

**1. ESRGAN (Enhanced Super Resolution Generative Adversarial Networks)**

Training within the ESRGAN model is conducted using Python to generate high-resolution images

**2. Supervised Machine Learning (K-Means Clustering)**

K-Means clustering of images using Python (.ipynb) to generate RGB coordinate information, pixel count, and color wheel visualization.

**3. Unsupervised Machine Learning (Neural Networks)**

Extraction of grayscale values and RGB values and train it to Neural Networks to classified batik textile's regional origin.

# Other usefull folder
1. ESRGAN model
https://github.com/xinntao/ESRGAN

2. High-resolution images of all 110 batik textile
https://drive.google.com/drive/u/0/folders/1AwEIlBSvHiiHOBWALd1avAdWiXYlsM1b

3. K - Means Clustering for all Batik Textile's images
https://drive.google.com/drive/u/0/folders/18rX9qR-_3-0HR-LxTp9Zk8QTfY2BVvGp

4. Color Wheels for all Batik Textile's images
https://drive.google.com/drive/u/0/folders/1FaeSOfRiXf_7NW1isofSmaplk8xFdLop

5. Data training for model classification from extracted RGB and greyscale coordinate
https://drive.google.com/drive/u/0/folders/1jgTDJ0uD1pjhebAKrfLwoFgy2Zw4SxJZ

# Conclusion
1. Classification model has 1.0 model accuracy and 100% dominant classification accuracy
2. It is possible to know about the batik's origin from its extracted color coordinate

# Recommendations
Very high accuracy is due to the very low number of databases (110) and a balanced dataset (55 Solo batik and 55 Garut batik). It is necessary to add training data to a minimum of 1000 from various batik patterns in Indonesia.


# Presentation
Full presentation for my final project:

https://bit.ly/13319061_PresTA
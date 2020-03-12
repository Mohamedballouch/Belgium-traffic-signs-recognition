# Belgium-traffic-signs-recognition

This project was created for the ML course at Institut National des postes et télécommunications MOROCCO. It's goal was to get in touch with artifical intelligence and neural networks based on the Belgian Traffic Sign Dataset and get better accuracy than the existing algorithm using Tensorflow and Keras. 

# 2. Project description

Trainging Dataset We are using the Belgian Traffic Sign Dataset. Go to http://btsd.ethz.ch/shareddata/ and download the training and test data. There is a lot of datasets on that page, but you only need the two files listed under BelgiumTS for Classification (cropped images)":

BelgiumTSC_Training (171.3MBytes) BelgiumTSC_Testing (76.5MBytes) After downloading and expanding the files, your directory structure should look something like this: /Training/ /Testing/

Each of the two directories above has 62 sub-directories named sequentially from 00000 to 00062. The directory name represents the code (or label) and the images inside the directory are examples of that label. The Training directory contains sub-directories with sequental numerical names from 00000 to 00061. The name of the directory represents the labels from 0 to 61, and the images in each directory represent the traffic signs that belong to that label. The images are saved in the not-so-common .ppm format, but luckily, this format is supported in the skimage library.

Image examples from database

![image](https://user-images.githubusercontent.com/28219393/76519720-8f36bd00-6472-11ea-92f3-857389a6c3d4.png)

![image](https://user-images.githubusercontent.com/28219393/76519770-a8d80480-6472-11ea-9b15-a6f5ef71e312.png)

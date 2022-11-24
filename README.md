# Clothing_image_classifier_Tensorflow
Unsupervised deep learning project that classifies clothing types using Tensorflow and the Keras API

This is the begining of a long term project to create a grading system application. 
The application is for items of clothing for sale on online sales platforms and I hope for it to be implemented to many suppliers.
The application will take data from the seller, via scraping or prefereably API on the clothing type, where it was made and what it is made from.
This data combined with human rights and environmental risk indexes. 
Then it will give the item a rating and inform the buyer for the real cost of that cheap t-shirt or dress.

Currently the project is in the infantile stages of image classification.
Using Tensorflow and the Keras API I have categorical model accuracy accross 10 catergorys of 0.84.
All tests of the model have predicted the correct model.

![image](https://user-images.githubusercontent.com/105222741/203861043-93ae3156-7d69-4ec2-b320-5d0b6fed4002.png)


Future steps are to increase the categories and use the [larger data](https://github.com/alexeygrigorev/clothing-dataset) set available with 20 catergories.

You can visit the online version running on ![Kaggle.com ](https://www.kaggle.com/nathanaustin/clothing-image-classifier-transfer-learning-model)

if you wish you can clone the repo, pip install requirements.txt and run the notebook ( non GPU notebooks beware) 

Acknowledgements ![alexeygrigorev](https://github.com/alexeygrigorev/clothing-dataset-small)

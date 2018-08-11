# ObjectDetectionWithSocialMedia
This project find objects in Instagram and Twitter user's images using CNN.

* This project provides receive images from Twitter and Instagram users, and then save this images to mongodb.
First of all, we are collecting images from users with social media. In this way, we will have a lot of images with specific tag.
* Secondly, this application gets images from mongodb each specific time interval, then it finds objects in images, and it replies post of users.
In the replied comment, predicted object name and its accuracy are written.

----- Requirements -----

* 1- Python 3 
* 2- Numpy
* 3- PIL
* 4- Tensorflow
* 5- Keras
* 6- Flask
* 7- Tweepy (for connect to Twitter api)
* 8- Pymongo

-> If the libraries described above have been successfully installed, you can run this project. Also, you must have a mongodb URI, twitter api keys and instagram access token.

* Optional: If you want to upload this project to Google App Engine, you must create requirements.txt(libraries described above with its versions) and .yaml file. For more informations, you can see this links; https://cloud.google.com/appengine/docs/standard/python/config/appref
https://cloud.google.com/appengine/docs/flexible/python/using-python-libraries

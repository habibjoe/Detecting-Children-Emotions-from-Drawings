![chld](https://user-images.githubusercontent.com/80888688/207580344-8a5ecf54-eecd-4787-bb52-98333b0e0ddd.jpg)
# **Detect children’s emotions through drawings**
Detecting children’s emotions through their drawings is an old technique and very used by psychology professionals.
Drawings give us a tremendous idea about children’s fears, joys, nightmares, experiences and also personalities. 
A drawing contains every key information about them.This technique has been here for over six decades.
Psychiatrist Miles Porot created it in 1951 and it’s now one of the most common techniques used to evaluate the personalities of children between 5 to 16.


# **Artificial Intelligence in Drawing techniques**
After reading about this interesting topic, we came up with the idea of combining the old technique and Artificial Intelligence to create a mobile app 
based on AI to detect different children’s emotions, extracting representative features from each category,
so we can decode children’s drawings and assign an specific emotion.


# **Solution**
"Saghiri" which mean mychild in arabic is a mobile application developed with Flutter, in which we integrate a tensorflow model,

# The model 
In this model we build a convolution neural network to classify drawings into emotions,
we found that there are many emotions a child can express,but in our model we decide to focus on 3 categories:
- Happiness
- Anxiety and Depression
- Anger and Violence
After some epochs and tuning the model to work well with our dataset, results were good, reached an accuracy of 87%!
![cpt](https://user-images.githubusercontent.com/80888688/207592278-f78204f9-7afc-4e33-a907-cdcd7aeac3b4.jpg)


# The application
After we finish the model we upload it as a tflite file in the purpose to integrate it in the Flutter code, and finally 
we get the newt result:
![test1](https://user-images.githubusercontent.com/80888688/207585776-14b75700-d84d-4dd8-89af-4cf22b7750e0.jpg)

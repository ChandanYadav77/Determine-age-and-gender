# Determine-age-and-gender
About Gender and Age Detection Project:
Due to the rise of social platforms and social media nowadays, there is also an increase in the number of applications that want automatic age and gender classification. As we know, age and Gender are two key facial attributes that play a very important role in social interactions.

So, in this deep learning project. we will be creating real-time gender and age detection using Deep Learning, and also in this, we will be using pre-trained models that classify the gender and age of the person. So the model will predict the gender as ‘Male’ and ‘Female’, and the predicted age will be in one of the following ranges- (0-2),(4-6),(8-12),(15-20),(25-32),(38-43),(48-53),(60-100) ( so there are 8 nodes in the final output layer or say softmax layer).

It is very difficult to predict the exact age of the person due to many reasons like (makeup, light, facial expressions, etc.) so that’s why we have considered this as a classification problem instead of a regression problem.

The process we will follow to create this Python project is that:
First we detect faces,
Predict their Gender (Classify them into Male/Female)
Predict their Age ( Classify them into 8 age ranges that is mentioned above)
And at last put the results on the person’s face and display it.

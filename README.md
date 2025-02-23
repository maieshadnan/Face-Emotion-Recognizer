# Face Emotion Recognizer
A face emotion recognizer built with TensorFlow and CNNs. This model achieved an accuracy of 80-90 on training data and 66 on validation data. I built it with 4 blocks of CNNs (Convolutional  Neural Networks) with Max Pooling. This can achieve pretty good results (Fun fact: I tested on my face and it was right!) and I am pretty happy with it. Try it on your own face too! :D<br />
Also, there are seven categories this model will classify your face into: Angry, disgust, fear, happy, neutral, fear, surprise. Also, for checking which category the model classified the face into use this:<br/>
```python
ds_train.class_names[pred] # where pred is the prediction
```
<br/>
Make sure to convert to grayscale, resize the image to 48 by 48, and add two dimensions. After that, your shape should be this:<br/>
(1, 48, 48, 1)<br/>
<br/>
<b>Author</b>: Muhammad Aiesh

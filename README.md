# Emoji-Prediction

In this project, I have implemented sentiment analysis for text classification so as to predict the corresponding emoji, by building an architecture with 2 LSTM layers and a dense layer (5 neurons) with softmax activation for classification.

#### Note : You need to download Glove Vectors. (https://www.kaggle.com/watts2/glove6b50dtxt) 

### Dependencies :
      1. Numpy 
      2. Emoji(library)
      3. Keras
      4. TensorFlow
      5. GloVe vectors
      6. Pandas
      
All the required test/train files are included.


## Model 
In this project, 2 LSTM layers are used, the first one to extract the context out of words and second one to combine all of them and produce final context, which is then connected to a Dense layer, for final output.

Dropouts have been added so as to reduce the paramneters during training (Training Data is somewhat less).

The five emojis used are :

    1. Heart emoji
    2. Upset emoji
    3. Fork and Knife
    4. Happy face
    5. Ball


## Results 

Using this model, we can do a good generalization of the predicted emojis.
<br>
<br>
<br>

<img src="https://github.com/Rahul2k/Emoji-Prediction/blob/master/2020-04-26.png" >

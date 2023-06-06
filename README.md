# Yachay.ai Task - Geolocation Prediction from Tweets
![alt text](https://github.com/giova22i/Yachay.ai-Task/blob/main/images/companyimage.png)

## Objective 

This project takes on the goal to improve upon Yachay.ai's infrastructure to train a deep learning model to predict coordinates of individual texts.

The first suggested methodology on training the model is to look into the annotated data set on texts posted from across North America. The goal is to identify the location of the user: be that by predicting an exact geopoint, or make a broader, region-based estimate 

## Models Evaluated 
     BERT 
     BERT multilingual 
     XLM RobERTa



## Insights
- Embeddings made using XLM performed better on a base neural network predicting geolocations
- A NER pipeline with better results would also likely increase the model performance. 
- More hyperparameter tuning, could help to achieve a better result
- More data per user would also aid in improving the model



## Libraries used
  
    Hugging Face 
    Haversine Distance
    BERT Tokenizer
    RoBERTa Tokenizer
    Tensor Flow
    Keras
    Adam
    K Means
    MENET
    LSTM
    Convolutional Neural Network
    Plotly Express
    Pandas
    Streamlit

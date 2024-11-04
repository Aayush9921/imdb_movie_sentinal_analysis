# End To End Project

## IMDb Movie Review Sentiment Analysis using Simple RNN

### Project Overview
This project classifies movie reviews into positive or negative sentiments using deep learning. A Simple RNN model is used due to its effectiveness with sequential data. By learning from labeled IMDb reviews, the model captures patterns associated with sentiment, helping understand audience reactions more effectively.

### Model Deployment Screenshot
Link : https://imdbmoviesentinalanalysis-btzbq7kgajdfhgngkzjbbd.streamlit.app/

![alt text](<Screenshot (63).png>)

### Dataset
The dataset used is the IMDb Movie Review Dataset, which contains 50,000 reviews labeled as either positive or negative. We split the dataset into training and testing sets to evaluate model performance.

### Model Architecture
The model uses a Simple RNN architecture, consisting of:

1. Embedding Layer: Converts words into dense vectors of fixed size, capturing semantic meaning.
2. Simple RNN Layer: Processes sequential data, maintaining information across steps to capture context.
3. Dense Layer: Fully connected layer with a sigmoid activation function to classify the sentiment as positive or negative.

### Training
The model is trained with the following parameters:

1. Loss Function: Binary cross-entropy, as it’s suitable for binary classification.
2. Optimizer: Adam optimizer for efficient gradient descent.
3. Metrics: Accuracy to track the classification performance.

### Deployment on Streamlit Cloud
This project is deployed on Streamlit Cloud, allowing for easy access and interaction with the sentiment analysis model through a web-based interface. Using Streamlit, we create an intuitive front end where users can input a movie review, and the model will classify it as positive or negative in real-time.
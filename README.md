# Spam_Question_Classifier

I have made this project in jupyter because the allocated RAM exceeded in my Google Colab account. I loaded the csv file as usual and used Keras tokenizer to create tokens. I then padded and created a sequential matrix for my data. 

Then, I downloaded a pre-trained word embedding called word2vec and used the 'word2vec-google-news-300' model. After splitting the data into train, test and validation, I trained the model. The custom pre-trained embedding was used in the Embedding layer with a Global Average Pooling to reduce training parameters. I got a validation accuracy of 95& and precision around 68%. The confusion matrix on test data revealed that TN = 362095 and TP = 12348.

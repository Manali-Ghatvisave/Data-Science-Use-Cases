#spam_vs_ham_using_LSTM

- kaggle Dataset :- https://www.kaggle.com/uciml/sms-spam-collection-dataset



# a good first step when working with text is to split it into words. words are called tokens and the process of splitting text into tokens is called Tokenization.

#Keras provides the text_to_word_sequence() function that you can use to split text into a list of words.

#keras Embadding Layer. Keras offers an Embadding layer that can be used for neural networks on text data. It requires that the input data be integer

encoded, so that each word is represented by a unique integer. It can be used to load a pretrained word embedding model, a type of transfer learning .

#A callback is a set of functions to be applied at given stages of the training procedure. You can use callbacks to get a view on internal states and statistics of the model during training. You can 

pass a list of callbacks(as the keyword argument callbacks) to be . fit() method of Sequential or Model classes. The relevant methods of the callbacks will then be called at each stage of the training.



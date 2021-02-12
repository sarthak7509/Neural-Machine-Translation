# Neural-Machine-Translation
## About
It is an algorithm to encode english akka Input Lang and Hindi akka Target Lang is such a way that when a specific english word is passed through the model it perfectly map that word
into its specifc hindi word. Although my dataset is not that big ie it does not constitute of all words of english but it can be seen as small representation of how translators could
be used to do the work.
Imagin there will e dictionary of million of words and numbers and trained on it that way it can be made as an perfect translator
## More about it
The above repository consist of two ipynb notebook an pretrained weights for both encoder and decoder and the original dataset be sure to unzip all of it and change there paths if needed
. The encoder and decoder weights are trained on 50 epochs and there working PDF will be released as Soon as possible
. If you want to train on local machine be sure I have trained them on GOOGLE COLAB and tested on my local Machine Tensorflow and keras version are given below:-
1)tensorflow=2.4.0
2)keras=2.3.1
## Things That Can Be Customized:-
You are welcome to customize. Embedding dim RNN units and Batch size that fits in your system if you have memmory allocation problem because that is most likely to happen 
and you can also switch input lang and targ lang in this way you can make hindi-english translation and also can use customized dataset 

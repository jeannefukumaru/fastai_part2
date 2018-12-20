# Lesson 6 takeaways 
- Build a character RNN from scratch with PyTorch 
- Understand the `Learner` class in PyTorch 
- concatenate inputs to hidden layers instead of adding inputs together 
- abstract the need to manually write for loops of FC layers with Pytorch's `rnn` class 
- overwrite the randomly initialised hidden-hidden weight matrix with an identity matrix 

# Lesson 8 takeaways 
- spend time getting bounding box coordinates into useable format 
- first step - write functions to display data and annotations to allow fast exploration 
- use dictionary comprehensions
- use `imageclassifierdata.from_csv`
- to create bounding box model 1. create model with 4 continuous outputs 2. create loss functions that
is lower is those 4 outputs are near to 4 other numbers
- PathLib JSON
- Defaultdict
- Lambda function 

TODO - learn how to navigate through fastai library source code 
     - learn how to use Python debugger to set traces and debug code with hotkeys

# Lesson 10 takeaways 
- process text by downloading corpus, 
- train a language model on data that learns structure of a language by taking in a token and predicting the token that comes next.
- unfreezing layers of a pre-trained language model 
- multi-batch RNN 

# Lesson 11 takeaways 
- output of (English) encoder layer h, is passed into (French) decoder along with previous French word predicted by the decoder 
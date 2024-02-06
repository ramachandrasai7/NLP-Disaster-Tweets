# NLP-Disaster-Tweets
Finding out whether the tweets given are saying about actual disaster or not
Train Data
-> Parameters id, keyword, location, text, target.
Text Column contains the actual tweets
Tokenizer - Twitter TweetTokenizer
Embeddings - Word2Vec
Architecture - LSTM(64)-> Dense(32) -> Dense(2)
Optimizers - RMS Prop
loss - binary_crossentropy

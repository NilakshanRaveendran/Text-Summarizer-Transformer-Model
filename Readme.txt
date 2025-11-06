This is a transformer model for text classification using TensorFlow and Hugging Face's Google's T5 small Transformers library.

This project fine-tunes the T5-small transformer on news articles to produce abstractive summaries: 
it tokenizes articles and reference highlights, trains a seq2seq model with Hugging Face's Trainer, 
and uses beam search to generate summaries. The notebook includes dataset loading, 
preprocessing, training, one-sample inference with ROUGE evaluation, and model saving 
for later use.
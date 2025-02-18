What libaries do you need to creat a Model?

import torch
import torch.nn as nn
import torch.nn.functional as F

What is an LLM?
A transformer based model trained on test dataset

What is an LLM in practise?
A text completion model that attempts to predict the next token in a sequence based on probabilities 

What is tokenization?
An algorithm that splits raw text into a sequence of words (tokens)
Each word gets feed into the models vocabulary which stores all words that our model needs which it then receives an integer representation (token) each word is converted to an integer 

What are the text tokenizer techniques?
-Tokenization on a word level
-Tokenization on a character level

How to build tokenizer?
What are examples of tokenizers?
TikToken - OpenAI, SentencePiece - Google



Resources: https://www.manning.com/books/build-a-large-language-model-from-scratch?utm_source=raschka&utm_medium=affiliate&utm_campaign=book_raschka_build_12_12_23&a_aid=raschka&a_bid=4c2437a0&chan=mm_github
https://medium.com/@msouza.os/llm-from-scratch-with-pytorch-9f21808c6319



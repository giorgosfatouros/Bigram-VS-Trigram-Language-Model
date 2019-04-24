# bigram-VS-trigram-language-model-for-word-sequences

i) Implement of a bigram and a trigram language model for word sequences (e.g., sentences). Train the models on a training subset of a corpus (e.g., from the English part of Europarl:http://www.statmt.org/europarl/). Include in the vocabulary only words that occur, e.g., at least 10 times in the training subset; use the same vocabulary in the bigram and trigram models. Replace all out-of-vocabular (OOV) words (in the training, development, test subsets) by a special token *UNK*. 

ii) Check the log-probabilities that the trained models return when given (correct) sentences from the test subset vs. (incorrect) sentences of the same length (in words) consisting of randomly selected vocabulary words.

iii) Estimate the language cross-entropy and perplexity of the models on the test subset of the corpus, treating the entire test subset as a single sequence, with *start* (or *start1*, *start2*) at the beginning of each sentence, and *end* at the end of each sentence. 

iv) Combine your two models using linear interpolation and check if the combined model performs better.

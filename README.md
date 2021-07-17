# POS-tags
Run the program with default command in Python 2.

The system uses the training corpus WSJ_02-21 to generate a prior probability table, a likelihood table, as well as a list of all the words in the training corpus.
The system is trained on the corpus and tested on the development corpus WSJ_24.
OOV items are handled by the distribution of all items occurring once as the basis of computing likelihoods.

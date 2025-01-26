# NLP Project 2

Spring 22. Done with Gal Katz.

In this project we wroked with the ATIS dataset. Given a query, our task was to predict the part of speech types from a known set of types. Meaning, our target was a sequence labeling, for each part of the sentence to fit the corresponding question type.

Note: We included among the tags the auxiliaries 'eos', 'bos', 'unk', 'pad' and 'O' (other, not related to any other type).

First we verified our majority baseline, which was about 63%. Not surprising, the tag 'O' was the most common.

Later, we implemeted three methods to deal with the task and compared those in the terms of performance, optimization, and computation time:

1. HMM.
2. RNN
3. LSTM

To conclude, we measured the performance and computation time of each model, while discarding different ratio of training data.

The whole implementations as well as the conclusions can be found in the notebook.

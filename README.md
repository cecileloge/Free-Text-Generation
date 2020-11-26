# Exploring ways to Generate Free Text Conditionally & Unconditionally

*Stanford CS230 Project*  

----

Text generation is a common task in many NLP domains, ranging from text summarization to machine translation or even poetry generation. Our goal is to design an efficient language model to generate short text snippets in the form 2-3 sentences summarizing the plot of a movie (similar to a synopsis we would find on IMDb): ideally, the snippets would both make sense and be imaginative.  In this study, we train several models with diverse architectures - RNNs with and without Attention, Gated CNN with Residual - on thousands of movie snippets of various lengths and genres - teaching them to take a few words as input and output a probability distribution for what the next word should be. 

Among the various questions that this goal entails, one particular challenge stands out: how can we control the output of the model in a consistent manner (e.g. generating a movie synopsis for a particular genre) without restricting creativity, or renouncing structure and grammar? Inspired by previous work on this topic, we also explore ways to condition the outputs of our models on a specific genre (e.g. comedy, horror, action), including an Encoder-Decoder architecture that proves more efficient than expected.

----


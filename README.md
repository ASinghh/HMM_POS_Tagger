# HMM_POS_Tagger
A python implementation of Hidden Markove Model for Parts of Speech Tagging. The project is a part of the Udacity's Natural
Language Processing Nanodegree. Project starts with Most Frequent Class Tagger and proceeds to a pomegrannate implementation
of Hidden Markov model using probability functions which are also defined in the same notebook. Smoothing and other
performance enhancing methods are also explored in the notebook.

<br/>

## Hidden Markov Models
Hidden Markov Model (HMM) is a statistical Markov model in which the system being modeled is assumed to be a Markov process
with unobservable (i.e. hidden) states.

The hidden Markov model can be represented as the simplest dynamic Bayesian network. The mathematics behind the HMM were
developed by L. E. Baum and coworkers. HMM is closely related to earlier work on the optimal nonlinear filtering problem by
Ruslan L. Stratonovich, who was the first to describe the forward-backward procedure.

In simpler Markov models (like a Markov chain), the state is directly visible to the observer, and therefore the state 
transition probabilities are the only parameters, while in the hidden Markov model, the state is not directly visible, but 
the output (in the form of data or "token" in the following), dependent on the state, is visible. Each state has a 
probability distribution over the possible output tokens. Therefore, the sequence of tokens generated by an HMM gives some 
information about the sequence of states; this is also known as pattern theory, a topic of grammar induction.

The adjective hidden refers to the state sequence through which the model passes, not to the parameters of the model; the 
model is still referred to as a hidden Markov model even if these parameters are known exactly.

Hidden Markov models are especially known for their application in reinforcement learning and temporal pattern recognition 
such as speech, handwriting, gesture recognition, part-of-speech tagging, musical score following, partial discharges and 
bioinformatics.

A hidden Markov model can be considered a generalization of a mixture model where the hidden variables (or latent 
variables), which control the mixture component to be selected for each observation, are related through a Markov process 
rather than independent of each other. Recently, hidden Markov models have been generalized to pairwise Markov models and 
triplet Markov models which allow consideration of more complex data structures and the modeling of nonstationary data.




## Data
Brown Corpus is used to train the model. The Brown University Standard Corpus of Present-Day American English (or just Brown Corpus) was compiled in the 1960s by Henry Kučera and W. Nelson Francis at Brown University, Providence, Rhode Island as a general corpus (text collection) in the field of corpus linguistics. It contains 500 samples of English-language text, totaling roughly one million words, compiled from works published in the United States in 1961. Brown corpus is accessed using the Natural Language Tool Kit (NLTK) package. Preprocessed tag and word files were used from the Udacity workspace.





## Modelling Software
Pyhton

### Packages Used
* matplotlib
* numpy
* IPython
* itertools
* collections
* pomegranate
* NLTK

### Custom Function File
* Helper.py





## Hardware
* Udacity's GPU workspace
 




## Results
We Observed the following results from the modelling exercise

### Training Accuracies
* Most Frequent Class Tagger    0.9572
* Hidden Markov Model Tagger    0.9753

### Testing Accuracies
* Most Frequent Class Tagger    0.9302
* Hidden Markov Model Tagger    0.9594






## Conclusion
Hidden Markov Model performs better than the Most Frequent Class Tagger. Achieved a test accuracy of 95.94%

# HMM_POS_Tagger
A python implementation of Hidden Markove Model for Parts of Speech Tagging. The project is a part of the Udacity's Natural
Language Processing Nanodegree. Start with Most Frequent Class Tagger and proceed to a pomegrannate implementation of Hidden-
Markov model using probability functions which are also defined in the same notebook. Smoothing and other performance enhancing
methods are also explored in the notebook.


## Modelling Software
Pyhton

### Packages Used
* matplotlib
* numpy
* IPython
* itertools
* collections
* pomegranate

### Custom Function File
* Helper.py


## Hardware
* Udacity's GPU workspace
 


# Results
We Observed the following results from the modelling exercise

## Test RMSE
* OLS     0.722622
* Lasso   0.669559
* Ridge   0.679769
* PCR     0.694552

## Importance of predictiors
The 5 most important predictors, based on their P-scores, in their order of importance, are  

1. Avg_surf aceArea,
2. FP067,
3. NumNonHBonds,
4. FP068,
5. FP091.

# Conclusion
For our use-case, we found Ordinary Least Square method to be the most effective Linear method to model chemical solubility.
 For detailed project report, please read <strong>predicting-chemical-solubility.pdf</strong>.

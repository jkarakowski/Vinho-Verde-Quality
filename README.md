#### Vinho-Verde-Quality

This is an analysis of UCI's Vinho Verde dataset (publicly available [here](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)).  The objective is to predict a wine's quality (rated from 1 to 10) based on quantitative measures such as pH.  The exercise was based on the discussion in Chapter 6 of *Machine Learning with R* by Brett Lantz.

The analysis is done in Python using several standard packages, including pandas, numpy, and scikit-learn.

After loading the data into a pandas dataframe, a decision tree is created and optimized.  The results are compared with a neural network.

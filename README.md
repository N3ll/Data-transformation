# Data transformation

Data sampling:
- without replacement
- with replacement

Data normalization and standartization:
- min-max normalization ([Xi - min(X)]/[max(X) - min(X)]) - the values will be between 0 and 1; guarantees all features will have the exact same scale but does not handle outliers well.
- z-score normalization (Xi - mean(X)/ std(X)) - ranges between -3 and -3 the mean of a z-transformed sample is always zero; handles outliers, but does not produce normalized data with the exact same scale.
- normalization by decimal scaling  

## Python version

Python 2


*Wrote during participation in the course Data Mining by University of Notre Dame, College of Engineering*

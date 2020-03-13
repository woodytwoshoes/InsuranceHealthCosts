Michael Woodburn: I'm seeking to explore and improve upon the work done by the great Dandelion https://www.kaggle.com/hely333/eda-regression/notebook in her analysis of insurance costs.

_________________________


Approach:
1. Start where Dandelion left off
2. One-hot encode the regions. I'm insticntively averse to creating a linear series of categorical variables.
3. Scale the data
4. Try other regression models (KNN)
5. Try new kernals (polynomials of degree>2)

Successes:
1. Improved upond Dandelion's R2 score with scaling
2. Noted some discrepancies in the data that indicate it is simulated

Learned:
1. Seaborn is a fantastic data visualisation tool. Especially for histogram-like representations


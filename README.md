# STAD80: A Review of Preetum Nakkiran's "More Data Can Hurt for Linear Regression: Sample-wise Double Descent"

## Authors

- Shawn Santhoshgeorge
- Anaqi As Shafiq Bin Amir Razif

## Summary

In overparameterized linear regression, the phenomenon of double descent can be observed were the Test MSE initially decreases with a fixed parameter ![equation](https://latex.codecogs.com/png.image?%5Cinline%20%5Cdpi%7B110%7D%7B%5Ccolor%7BWhite%7D%20d%7D) and an increasing sample ![equation](https://latex.codecogs.com/png.image?%5Cinline%20%5Cdpi%7B110%7D%7B%5Ccolor%7BWhite%7D%20n%20%7D). It keeps on decreasing before increasing asymptotically towards infinity when ![equation](https://latex.codecogs.com/png.image?%5Cinline%20%5Cdpi%7B110%7D%7B%5Ccolor%7BWhite%7D%20n%20%5Capprox%20d%7D) before it begins decreasing again. We call the regime where ![equation](https://latex.codecogs.com/png.image?%5Cinline%20%5Cdpi%7B110%7D%7B%5Ccolor%7BWhite%7D%20n%20%5Cleq%20d%20%7D) to be the overparameterized regime and the underparameterized regime is when ![equation](https://latex.codecogs.com/png.image?%5Cinline%20%5Cdpi%7B110%7D%7B%5Ccolor%7BWhite%7D%20n%20%3E%20d%20%7D). There are interesting concepts that can be found when researching and analyzing these regimes especially around the area of ![equation](https://latex.codecogs.com/png.image?%5Cinline%20%5Cdpi%7B110%7D%7B%5Ccolor%7BWhite%7D%20n%20%5Capprox%20d%7D). This repository looks into the claims made in "More Data Can Hurt for Linear Regression: Sample-wise Double Descent" by Preetum Nakkiran. It includes the a deeper analysis on Section 3.1 of paper and works to explain the conclusions of the paper.

## Results

This graph was created based on a simple simulation based on the configuration stated in the paper and was a test to see if we could replicate the claims.

<center>
 <img src="./Paper/graph.png"/>
</center>

## References

- [More Data Can Hurt for Linear Regression: Sample-wise Double Descent](https://arxiv.org/pdf/1912.07242.pdf)

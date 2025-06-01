# Chance-Constrained Optimization

## Chance-constrained optimisation model

A chance-constrained problem can be written as

$$
\min_{x \in X}\;
      \Bigl\{\,f(x)\;:\;
      \mathbb{P}\!\bigl[\,G(x,\boldsymbol{\xi})\le 0\,\bigr]\le\alpha
      \Bigr\}.
$$

Let  

\[
p(x)\;=\;\mathbb{P}\!\bigl[\,G(x,\boldsymbol{\xi})\le 0\,\bigr],
\]

and estimate the probability with the empirical measure  
\(P_N = \tfrac1N\sum_{i=1}^N \delta_{\xi_i}\) based on the samples
\(\xi_1,\dots,\xi_N\):

\[
\hat p_N(x)
  := P_N\!\bigl[G(x,\boldsymbol{\xi})\le 0\bigr]
  = \frac1N\sum_{i=1}^{N}\mathbf 1_{(-\infty,0]}\!\bigl(G(x,\xi_i)\bigr).
\]

The sample-average approximation (SAA) of the original problem is therefore

$$
\min_{x \in X}\;
      \Bigl\{\,f(x)\;:\;
      P_N\!\bigl[G(x,\boldsymbol{\xi})\le 0\bigr]\le\gamma
      \Bigr\}.
$$

### References  

* **[1]** A. Shapiro, D. Dentcheva & A. Ruszczyński, *Lectures on Stochastic Programming: Modeling and Theory*, SIAM, 2014.  
* **[2]** R. Liu & A. Shapiro, “Sample average approximation of chance constrained programming: feasibility and stability,” *SIAM J. Optim.*, 2009.  
* **[3]** P. Kall & S. W. Wallace, *Stochastic Programming*, John Wiley & Sons, 1994.



This repository demonstrates an implementation of chance constrained portfolio allocation using the Sample Average Approximation (SAA) method for chance-constrained programming. The approach and methodology are based on the paper:  
["Sample Average Approximation Method for Chance Constrained Programming: Theory and Applications"](https://link.springer.com/article/10.1007/s10957-009-9523-6).

## Contents

- **Notebook**: Contains an interactive Jupyter notebook illustrating the portfolio optimization approach, step-by-step implementation, and results.
- **Source Code**: Supporting scripts for the main implementation.

## Reference

If you use this repository or find it helpful, please consider citing the referenced paper and this repository.

- Paper: [Sample Average Approximation Method for Chance Constrained Programming: Theory and Applications](https://link.springer.com/article/10.1007/s10957-009-9523-6)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

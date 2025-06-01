# Chance-Constrained Optimization


The problem of interest is a chance-constrained problem that may be formulated as follows:

    minₓ { f(x) : x ∈ X,  P[G(x, ξ) ≤ 0] ≤ α }

Let p(x) = P[G(x, ξ) ≤ 0], and note that the empirical probability distribution P_N may be used to estimate P.  
For realizations ξ₁, ξ₂, ..., ξ_N of ξ:

    p̂_N(x) := P_N[G(x, ξ) ≤ 0] = (1 / N) ∑_{i=1}^{N} 𝟙_{(-∞, 0]}[G(x, ξᵢ)]

The Sample Average Approximation (SAA) method to solve the above chance-constrained problem is generally formulated as:

    minₓ { f(x) : x ∈ X,  P_N[G(x, ξ) ≤ 0] ≤ γ }


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

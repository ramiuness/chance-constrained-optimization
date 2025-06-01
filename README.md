# Chance-Constrained Optimization

	Chance-constrained optimization is a powerful technique for making decisions under uncertainty. In portfolio allocation problems, chance constraints allow portfolio decisions to incorporate uncertainty explicitly by requiring that critical constraints (e.g., achieving a minimum level of return) be satisfied with high probability rather than deterministically, thus offering a more flexible and realistic way to handle risk in uncertain markets. This framework allows placing a VaR-style bound on portfolio returns.
 
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

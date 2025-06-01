# Chance-Constrained Optimization

The problem of interest is a chance constrained problem that may be formulated as follows:

![equation](https://latex.codecogs.com/png.image?\dpi{150}&space;\displaystyle\inf_x\{f(x):x\in&space;X,\,\,\mathbb{P}[G(x,\xi)\leq&space;0]\leq&space;\alpha\})

Let ![p(x)](https://latex.codecogs.com/png.image?\dpi{150}&space;p(x)=\mathbb{P}[G(x,\xi)\leq0]) and notice that the empirical probability distribution ![P_N](https://latex.codecogs.com/png.image?\dpi{150}&space;P_N) may be used to estimate ![\mathbb{P}](https://latex.codecogs.com/png.image?\dpi{150}&space;\mathbb{P}).

For realizations ![\xi_1,\,\xi_2,\,\dots,\,\xi_N](https://latex.codecogs.com/png.image?\dpi{150}&space;\xi_1,\,\xi_2,\,\dots,\,\xi_N) of ![\xi](https://latex.codecogs.com/png.image?\dpi{150}&space;\xi):

![p_hat](https://latex.codecogs.com/png.image?\dpi{150}&space;\hat{p}_N(x):=P_N[G(x,\xi)\leq0]=\frac{1}{N}\sum_{i=1}^{N}\mathbb{1}_{(-\infty,0]}[G(x,\xi_i)])

The SAA method to solve the above chance constrained problem is generally formulated as:

![saa](https://latex.codecogs.com/png.image?\dpi{150}&space;\displaystyle\inf_x\{f(x):x\in&space;X,\,\,P_N[G(x,\xi)\leq&space;0]\leq&space;\gamma\})


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

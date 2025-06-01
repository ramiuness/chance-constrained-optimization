# Chance-Constrained Optimization

Chance-constrained portfolio optimization provides a structured way to make investment decisions under uncertainty. Rather than requiring rigid constraints, it ensures key objectives—such as achieving a target return—are met with high confidence. This method closely aligns with modern risk management practices by incorporating Value-at-Risk (VaR) principles directly into the portfolio construction process, enabling more resilient and realistic strategies in volatile markets.
 
This repository demonstrates an implementation of chance constrained portfolio allocation using the Sample Average Approximation (SAA) method for chance-constrained programming. The approach and methodology are based on the paper:  
["Sample Average Approximation Method for Chance Constrained Programming: Theory and Applications"](https://link.springer.com/article/10.1007/s10957-009-9523-6).

## Contents

- **Notebook**: Contains an interactive Jupyter notebook illustrating the portfolio optimization approach, step-by-step implementation, and results.
- **Source Code**: Supporting scripts for the main implementation.

### 🛠 Tools & Technologies

#### 🖥️ Language  
![Julia](https://img.shields.io/badge/Julia-9558B2?logo=julia&logoColor=white)

#### ⚙️ Optimization Solvers  
![JuMP](https://img.shields.io/badge/JuMP-00BFFF?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyBmaWxsPSIjMDAwMDAwIiBoZWlnaHQ9IjEwMCIgd2lkdGg9IjEwMCIgdmlld0JveD0iMCAwIDEwMCAxMDAiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI%2BPC9zdmc%2B&label=JuMP)  
![HiGHS](https://img.shields.io/badge/HiGHS-0066CC?logo=gnu&logoColor=white)  
![Gurobi](https://img.shields.io/badge/Gurobi-EE1C25?logo=gurobi&logoColor=white)

#### 🎲 Simulation Techniques  
![Monte Carlo](https://img.shields.io/badge/Monte%20Carlo%20Simulations-FFD700?style=flat)

**Statistical Models**  
![GMM](https://img.shields.io/badge/Gaussian%20Mixture%20Models-6D4C41?style=flat&logo=scikit-learn&logoColor=white)

**Notebook**  
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

**Backtesting**  
![Rolling Window](https://img.shields.io/badge/Rolling--Window--Backtesting-4CAF50?style=flat)


## Reference

If you use this repository or find it helpful, please consider citing the referenced paper and this repository.

- Paper: [Sample Average Approximation Method for Chance Constrained Programming: Theory and Applications](https://link.springer.com/article/10.1007/s10957-009-9523-6)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

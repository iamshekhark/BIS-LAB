
# Grey Wolf Optimization (GWO)

## 1. Title
Machine Learning Hyperparameter Optimization Using Grey Wolf Optimization.

## 2. Research Paper Details
- **Paper Title:** Grey Wolf Optimizer
- **Authors:** Seyedali Mirjalili, Seyed Mohammad Mirjalili, Andrew Lewis
- **Journal:** Advances in Engineering Software
- **Volume:** 69
- **Pages:** 46–61
- **Year:** 2014
- **DOI:** 10.1016/j.advengsoft.2013.12.007

### Research Paper Links
- [Research Paper](https://www.sciencedirect.com/science/article/pii/S0965997813001853)
- [DOI Link](https://doi.org/10.1016/j.advengsoft.2013.12.007)
- [PDF Link](https://programstore.ir/wp-content/uploads/2018/07/GWO_finalVersion.pdf)

## 3. Problem Statement
A machine learning system requires suitable hyperparameters to improve its performance. Grey Wolf Optimization (GWO) is used to find the best learning rate, number of hidden neurons, and batch size by minimizing a fitness function.

## 4. Problem Objective
- Implement Grey Wolf Optimization using Python.
- Find the best combination of hyperparameters.
- Minimize the fitness value.
- Understand the hunting and leadership behavior of grey wolves.

## 5. Algorithm Description
Grey Wolf Optimization is a nature-inspired optimization algorithm based on the social hierarchy and hunting behavior of grey wolves.

The four types of wolves are:
- Alpha: Best solution.
- Beta: Second-best solution.
- Delta: Third-best solution.
- Omega: Remaining solutions.

## 6. Code Summary
1. Import the NumPy library.
2. Define a fitness function to calculate optimization error.
3. Initialize the number of wolves and iterations.
4. Generate random wolf positions.
5. Evaluate the fitness of each wolf.
6. Identify Alpha, Beta, and Delta wolves.
7. Update wolf positions using GWO equations.
8. Repeat the process for the specified iterations.
9. Select the best solution.
10. Display the best hyperparameters and minimum fitness value.

## 7. Output Summary
- Displays the best learning rate.
- Displays the best hidden neurons.
- Displays the best batch size.
- Displays the minimum fitness value.
- Demonstrates optimization using grey wolf hunting behavior.

## 8. Technologies Used
- Python
- NumPy

## 9. How to Run
```bash
pip install numpy
python GWO.py
```

## 10. Conclusion
Grey Wolf Optimization uses the social hierarchy and hunting behavior of grey wolves to find an optimal solution. It helps identify suitable machine learning hyperparameters by minimizing the fitness function.

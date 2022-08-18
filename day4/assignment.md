Run the EAs with problems provided by desdeo_problem.testproblems module.

Run the EAs with your own MOPs

Optional: Implement a simple EA as a subclass of BaseEA:
* Check out BaseEA: https://github.com/industrial-optimization-group/desdeo-emo/blob/master/desdeo_emo/EAs/BaseEA.py
* Write an __init__() method to accept the `MOProblem` class (handles MOP formulation) and initialize a `Population` class (handles creation and evaluation of offsprings and management of population) within it.
* Write a \_next_gen() method to run one generation of the algorithm. Check out the method with the same name in BaseDecompositionEA for inspiration (instead of conducting selection in a different method, you can do it within the same method).
* Use surrogate assisted optimization on a more challenging problem (more complicated function, noisy data, etc). You can create your own data or get the data from internet repositories.

* Compute a representative set of Pareto optimal solutions utilizing some evolutionary method, and then use that set in a scalarization-based method to choose the most preferred solution.

* Do the above but utilize a surrogate problem instead while computing the set of representative solution in the evolutionary method. How does this affect solving the problem in the scalarization-based method?

* Optional task: Modify one or more surrogate modelling techniques from Python packages such as sklearn and use it in DESDEO, compare results with the GaussianProcessRegressor (check out https://github.com/industrial-optimization-group/desdeo-problem/blob/master/desdeo_problem/surrogatemodels/SurrogateModels.py to see a very basic modification). You can try to implement ensemble models such as gradient boosted trees.
## Some tests on callibration algorithms ##
All the algorithms are based on [the method of the least square](https://en.wikipedia.org/wiki/Least_squares), which is a mathematical approach used in regression analysis to find an approximate solution of an overdetermined system. The methods is used to calculate a the coefficients of a 12-variable function. As it turns out the following approaches for minimizing the value of the function are needed:
### Steepest descent approach ###
Wolfram Mathematica code about the steepest descent approach can be found in [steepest_descent.kiwi](./steepest_descent.kiwi). As tests prove it is pretty hard to determine the global minimum of the function this way because the function is some sort of hyper surface with a lot of extremums.

# ML - genetic-algorithm
### Learning as a Search
There exists an optimization problem, which is described by the fitness function 
f(x; y) = 25 * (y + x^2)^2 + (1 + x)^2. In order to find an optimal solution you need to find the global minima of
this function with respect to the two variables 'x' and 'y'. They are real-number variables. Perform the following actions:

### 1.1. 
Build a plot of the function (Octave, Matlab, Python are good choices) and tentatively
define the possible area of global minima of the function. Make a hypothesis about the existing of
local and global optimal solutions.

### 1.2. 
Implement a simple Genetic Algorithm (GA), which will minimize the fitness function
and can deal with the real-values features. Crossover/Mutation operations and initial seed are up to
you. Try to use GA with the following parameters:
- size of population in each generation: 4, 10
- crossover operations per generation: 25%, 50% , 75%
- mutations per generation: 1%, 5% and 50% (or at least 1 element in the generation)
- total number of generations: 10, 100 or 1000
- selection of candidates with the best values of fitness function is performed after
crossover/mutation

### 1.3. 
Implement a simple Gradient Descent method. If you like, you may use an online tool or
library that calculates the partial derivatives for you. Try using the following parameters:
- Employ several stop conditions: absolute differences between the function values, absolute
differences between the arguments values and absolute differences between the first order
derivative values on adjacent steps.
- learning steps: 1e-6, 0.1, 1.
- maximal number of iterations: 100, 1000

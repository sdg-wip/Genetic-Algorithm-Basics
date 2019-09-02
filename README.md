# Genetic-Algorithm-Basics
Genetic Algorithms (GAs) are search based algorithms based on the concepts of natural selection. GAs are a subset of a much larger branch of computation known as Evolutionary Computation. Genetic algorithms simulate the process of natural selection which means those species who can adapt to changes in their environment are able to survive and reproduce and go to next generation.

The steps for genetic algorithms:

1. ***Initialisation:*** This is the process to choose initial population. popualtion comprises of individuals which is equivalent to chromosomes in context of biology and each chromosome consists of multipple gene.

2. ***Fitness Assignment:*** Each indiviual is evaluated based on score how fit they are. This is fitness score. We can define the score according  to our problem.

3. ***Selection:*** chromosomes from our population are selected which can mate and create their off-springs. This is not based on fitness score.
If we select only the fit chromosomes to produce off-springs, that would lead to chromosomes that are more close to one another in a few next generation, and therefore less diversity. Different selection methods are there **Roulette Wheel Selection method** being one of them.

4. ***Crossover:*** Crossover is the one of the significant phase in a genetic algorithm. For each pair of parents to be mated, a crossover point is chosen at random from within the genes. Offspring are created by exchanging the genes of parents among themselves until the crossover point is reached.

5. ***Mutation:*** a random tweak in the chromosome that increases diversity among the next generation is called mutation. Offsprings from the same parents doesn't become identical due to this mutation process.

The off-springs are again validated using the fitness function, and if considered fit then will replace the less fit chromosomes from the population.

The algorithm terminates if the population converges that means it doesn't produce off-springs which are significantly different from the previous generation. Then it is said that the genetic algorithm has provided a set of solutions to our problem.

GA does not require any derivative information to reach the optimal solution and hence useful for many optimization problem where derivative information can't be calculated. It optimizes both continuous and discrete functions and also multi-objective problems and provides set of solutions instead of any single solution. It is fast as it incorporates parralllel computing capabilities. This is very useful optimization technique for large search base with large number of parameters.

The main shortcoming of this technique is that there are no guarantees on the optimality of the solution as the the process is stochastic.


  

# Heart-Disese-Predicition Using Genetic Algorithm
**Tool Used:** Netbeans

This project basically involves genetic algorithm to find the fitness of the population over a period of time.

## Implementation

The use of Genetic algorithm isto improve the learning of the neuro-fuzzy system which makes the training fast and also enhances its performance. 
Genetic algorithms are commonly used for better solution due to its operators like selection, crossover and mutation.

1.Initialize population by selecting random individuals from the spaces.


2.for The specified number of generations do


3.for The size of the population do


4.Select two individuals (with uniform probability) as parent1 andparent2.


5.Apply crossover to produce a new individual(child).


6.Apply mutation to child.


7.Calculate the distance between child and parent1as


8.d1, and the distance between child and parent2 asd2.


9.Calculate the fitness of child, parent1, and parent2 as f, f1, and f2respectively.


10.if (d1 <d2) and ( f >f1)


then


11.replace parent1 with child


else


12.if (d2 <= d1) and ( f >f2)then


13.Replace parent2 withheld.


endif


endfor


Extract the best (highly-fitted) individuals as your final solution.


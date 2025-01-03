# Traveling_Salesman_Simulated_Annealer
VBA macro simulated annealer that solves the traveling salesman problem for up to 20 cities

On the UI sheet, pressing "minimize energy" will cause the simulated annealer to create a solution for 20 cities that attempts to minimize total travel distance.

On the UI sheet, pressing "test" will cause the simulated annealer to create 10 solutions for 20 cities with the same coordinate.

On the UI sheet, pressing "screensaver" will cause the simulated annealer to create solutions one after the other until you press escape. The program will create 10 solutions for 20 cities with the same coordinates and then randomly create 20 new city coordinates before starting over.

On the NN sheet, the buttons perform the same action but the various matrices used to perform the majority of calculates are visible.

On the NN sheet, if you press "test" you will see 10 routes generate for 14 cities (the most probably number the model will successfully generate). The routes will be displayed as projections in 20 dimensional latent space.

For more information:

[Blog article 1](https://gwyche.wordpress.com/2024/10/26/neural-network-traveling-salesman-solver/)

[Blog article 2](https://gwyche.wordpress.com/2024/11/10/hopfield-network-with-simulated-annealing/)

[Blog article 3](https://gwyche.wordpress.com/2024/12/07/simulated-annealer-some-observations/)


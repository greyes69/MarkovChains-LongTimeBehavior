## Generating sample paths of finite Markov Chains

This code simulates the dynamics of a finite Markov chain given:

- The size of the chain (K)
- The transition matrix
- The initial state (an integer between 1 and K)
- The number of time steps
- The number of simulations

Output:

- The  evolution of a of sample path
- The proportion of final states (histogram and actual values)

## Note: ## 

If the transition matrix is regular, the limit distribution (proportion) is the stationary one, given by the eigenvector with eigenvalue =1 (Perron-Frobenius Theorem). 


# Binomial-Pricing-Model-Project

This project implements a binomial option pricing model for valuing European and American call options. The binomial model is a discrete-time numerical method that approximates the price of an option by constructing a price tree for the underlying asset. At each time step, the asset can move up or down with a specified probability, and the option value is determined through backward induction.

The key difference between European and American call options lies in their exercise rights. A European call option can only be exercised at expiration, meaning its value is derived solely from the final step of the binomial tree. In contrast, an American call option can be exercised at any time before expiration, requiring an additional step in the model to check for early exercise at each node. This project not only computes option prices but also visualizes binomial trees against the stock price evolution, offering insights into option pricing dynamics.

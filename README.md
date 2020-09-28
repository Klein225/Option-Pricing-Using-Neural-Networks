# Option-Pricing-Using-Neural-Networks

## Thesis statement:
This is a thesis topic which studies option pricing using (possibly deep) neural networks with outset in McGhee (2018) "An Artificial Neural Network Representation of the SABR Stochastic Volatility Model" and particularly focuses on implementation in Python.

## Folders: 
The following folders will only contain the code used to compute the neural network and its corresponding results. The code has been writtein using Jupyter Notebooks in order for the reader to gain a better overview. If you would like to read the Thesis, please refer to the PDF.

### Black Scholes Merton:
Calculating the simple BSM call/put-prices as well as simulating using Monte Carlo and Artificial Neural Networks. The networks are based on the work by Antoine Savine (https://antoinesavine.com/category/machine-learning/) and William McGhee ("An artificial neural network representation of the sabr stochastic volatility model").
- BSM With a Stock
- ANN Antoine
- Ann McGhee
- BSM Monte Carlo

### Heston:
Implementing the Heston model using Fourier transform (Lewis and Lipton formula) as well as using the Brent method to deduce the implied volatilities. From that we generate 300-thousand datapoints for our ANN and 600-thousand datapoints for our DNN. Both the ANN and DNN are available in easy to understand implementations with comments. This folder will also contain the hyper-parameter tuning of our neural networks.
- Heston DNN
- Heston ANN
- Heston Hyperparameters
- Heston Setup

### SABR: 
Implementing the SABR Approximation (same as McGhees "An artificial neural network representation of the sabr stochastic volatility model"). from that we generate 300-thousand datapoints for our ANN. The ANN is available in easy to understand implementations with comments. This folder will also contain the hyper-parameter tuning of our neural network.
- SABR Approximation ANN
- SABR Integration ANN 
- SABR Hyperparameters
- SABR Setup

### Other:
Contains a bit of everything 
- Activation function comparison
- Activation functions
- Early stopping
- Gradient Descent
- Initializers
- Sobol

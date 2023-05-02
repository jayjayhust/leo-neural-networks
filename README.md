# leo-neural-networks

Please check out the corresponding Medium article to this repository.

## Initial neural network code

Please modify this code to run the inference for a multilayer perceptron neural network in the zk-SNARK circuit language Leo.

## Python neural network generator

Please use this Python 3 code to generate neural network architectures of arbitraty size for multilayer perceptron neural networks in the zk-SNARK circuit language Leo.

## credit_analysis_application folders

Please use these folders in combination with the German credit machine learning dataset. Use the Python folder first to generate the Leo program and inputs, and then run these in Leo.

## Articles
Loan decisions with neural networks using Leo: 
- ENG: https://www.aleo.org/post/loan-decisions-with-neural-networks-using-leo  
- CHN: https://www.yuque.com/maxsayss/aleowiki/ybirisx78byuhc9v?singleDoc=

## Procedure
1. Prepare the German credit machine learning dataset: https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)
2. Training the neural network using PyTorch and Python: leo-neural-networks/credit-analysis-application_python/01_train_neural_network.py
3. Evaluating the trained neural network: leo-neural-networks/credit-analysis-application_python/02_test_neural_network.py
4. Transferring the neural network to Leo: leo-neural-networks/credit-analysis-application_python/03_leo_circuit_generator.py
5. Generate neural network input data to Leo: leo-neural-networks/credit-analysis-application_python/04_extract_inputs.py
6. Generated input data file to Leo: leo-neural-networks/credit-analysis-application_leo/inputs/project.in
7. Evaluating the Leo neural network(leo run): leo-neural-networks/credit-analysis-application_leo

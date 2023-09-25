Instruction
1. Fill in Input.xlsx
2. Run payoff.ipynb or payoff.py to evaluation structure product with Monte Carlo simulation
    - Input: Input.xlsx
    - Output: Output.xlsx
    	- all the contracts in Input table: Output.xlsx[summary]
      	- individual contract: Output.xlsx[##user-defined name of the contract]

Description: 
1. MonteCarlo.py
    - Functions for Monte Carlo simulation for univariate and multivariate underlying
    - Other utility functions 
    
2. payoff.ipynb
    - This program evaluate the payoff of contracts in Input.xlsx and write outcome to Output.xlsx
    - It will rerun all contracts in Input.xlsx if Output.xlsx is not in the folder.

Outstanding Items
1. FXc (extract actual FXc or perform another simulation)
2. Coupon Barrier/Accumulate Feature

Link to Colab:
https://drive.google.com/drive/folders/1E43OCyUkc2njoVgLZSTNLCyYQB6rpJ6u 

# Monte Carlo Simulation-Optimal Production Level

The model is used to determine the optimal production level for a product with uncertain demand. Monte Carlo Simulation is used to generate demand scenarios and find the optimal production level that maximizes expected profit.

* Created a program simulation written in Python to generate a recommended production quantity based on the given set of parameters
* Parameters: unit price, retail price, cost of disposing, and number of units to manufacture

![alt text](https://github.com/dl754/Newsvendor-with-Monte-Carlo-Simulation--Optimal-Production-Level/blob/main/output.png)

## Table of Contents
1. [Background](#Background)
2. [Requirements](#Requirements)
3. [Usage](#Usage)
4. [Results](#Results)
5. [License](#License)

## Background

Your business analyst forecasts that the demand for TwoPlus Earbuds X is normally distributed with a mean of 150 and a standard deviation of 20. The total cost of manufacturing and logistics for each unit is $28.50, and you sell the earbuds at a retail price of $150.00. Any earbuds not sold within one month need to be disposed of in an environmentally sustainable way, which will cost the company $8.50 per unit

* Mean = 150
* Stdve = 20
* Total_Cost/Unit = $28.50
* Retail_Price/Unit = $150.00
* Salvage_Valie/Unit = -$8.50

## Requirements<a name="Requirements"></a>

* Python 3
* NumPy
* Matplotlib

## Usage

To run the simulation, simply input Command:
  simul = 1000
  ps = ProfitStimulation(simul)
  ps.loop_manufactured(). 
  
This will create an instance of the ProfitSimulation class with simul number of simulations, and then call the loop_manufactured method to perform the simulation and plot the results. You can adjust the value of simul to increase or decrease the number of simulations performed. Additionally, you can modify the parameters passed to the __init__ method of the ProfitSimulation class to simulate different scenarios.


## Results

![alt text](https://github.com/dl754/Newsvendor-with-Monte-Carlo-Simulation--Optimal-Production-Level/blob/main/output.png)


Optimal Production Units: 169, Maximized Profit: $17365.719

## License

MIT License

Copyright (c) [2023] [Konstantin Liu]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.


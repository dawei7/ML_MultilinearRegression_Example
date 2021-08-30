# ML_MutlilinearRegression_Example

For educational reasons and to track the Machine Learning regarding Multilinear regression under the hood.
1. Excel LinearRegressionSimulator
Tab 'Random_Data_Generator' with 11 variables x0-x10 and a "random" function y=245-5x<sub>1</sub>+2.87x<sub>2</sub>-87x<sub>3</sub>+333x<sub>4</sub>+1x<sub>5</sub>+7x<sub>6</sub>-55x<sub>7</sub>-10x<sub>8</sub>+4x<sub>9</sub>+10x<sub>10</sub>
2. In the second tab "Data" are the hardcorded data, to prevent any changing during the experiment. Rand() in Excel recalcuates every time you press into the cell.
Moreovber in this tabs there are the findings presented.
3. Goal and procedure
There are 50 rows with random generated numbers rand() from -1000 to +1000. the measure variable y is calculated with the the function above +/- 10% random noise.
The goal of this educational experiment was to find out, whether Machine learning can guess the original function correctly, even with noise.
The experiment was successful; the model from SKlearn found a close enough function.
Moreover I wanted to find the exact same function without sklearn, only with Calculus multivariate derivation.
With both ways I finally receive a very similar result. However, the pure mathematical way seems a bit too inefficient; somehow there are maybe some optimizations built in sklearn LinearRegressionModel() to find the optimum very fast.
Anyway, the excel and Jupyter Notebook does what it expects; it shows "What is Machine Learning" in the context of Multlinear Regression.

# gpLearningInAlphaResearch
It is a gpLearning project for alpha research

## Introduction
  I finished the code with jupyter Notebook. The main packages are Numpy, Pandas and gpLearn in python 3.11.2. The gp algorithm is divided into 6 parts.
  - Make Function: I defined severval functions that are not included in gpLearn, such as decay, rank, correlation which are important in quantitative alphas mining. More functions can be added if needed.
  - Preprocess of Dataset: There are two datasets you should define: varibles(X) and targets(Y), In the test part, I tried "open","close" as X and 1-day return for stocks with vwap data.
  - Fitness Function: You need to define a fitness function, such as IC, RankIC or IC/IR.
  - gpModel: Based on the parameters, the model will be built and numerous expressions will be generated.
  - Tested: It is under development. 

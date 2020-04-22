# santa-workshop-tour-2019
 Kaggle competition santa-workshop-tour-2019 using a original development of Genetic Algorithm
 
 My shared Notebook on Kaggle : https://www.kaggle.com/jeugregg/santa-s-2019-original-genetic-algorithm-method 
 
 Competition : https://www.kaggle.com/c/santa-workshop-tour-2019/
 
 This competition is about schedule optimization.
 I compare my original method and Gurobi optimizer method.
 You can read my report & presentation (in French) in [/doc/ folder](https://github.com/jeugregg/santa-workshop-tour-2019/tree/master/doc)
 
santa-s-2019-starter-notebook.ipynb  notebook contains :

    main fonction to optimize schedule of santa tour 2019 KAGGLE competition : (Loop over Generation part)
    a lot of sub-functions used by genetic algo main in Useful functions, Prepare mutation and Cost function parts.
    cost function optim is based on kaggle kernel: https://www.kaggle.com/xhlulu/santa-s-2019-faster-cost-function-24-s
    C++ Stochastic Product Search is base on kaggle kernel : https://www.kaggle.com/golubev/c-stochastic-product-search-65ns & https://www.kaggle.com/dmintry/c-stochastic-product-search-in-few-threads
    Most of the python functions are numba optimized

	VERSIONS :
    V3.2: 15/02/2020 : fixe sps add-on extend range choices
    V3.1: 15/02/2020 : impove sps add-on
    V3.0: 12/02/2020 : add stochastic product search boost
    V2.1: 04/02/2020 : correction fun_vect_mut
    V2.0: 03/02/2020 : random path population generation
    V1.1: 03/02/2020 : @njit(parallel=True)
    V1.0: 03/02/2020 : update generate_crossing_prob (optimize perf.)
    
santa_gurobi_01.ipynb : Notebook about  Test Gurobi MIP Optimizer
	
	 Reused with different seeds from :  
	 https://towardsdatascience.com/helping-santa-plan-with-mixed-integer-programming-mip-1951386a6ba5



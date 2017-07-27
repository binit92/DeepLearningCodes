# DeepLearningCodes
 Projects from Udacity- DeepLearning Foundation Nanodegree Programme

## Installation
 To run this files succesfully , You can get started with Anaconda, and Jupyter notebook

* [Anaconda](https://www.continuum.io/downloads) - A package, dependency and environment manager 

	**Useful commands** 
	```
	conda list - 
	conda upgrade conda 
	conda upgrade --all

	conda install numpy 
	conda install numpy=1.10
	conda remove numpy
	conda update numpy
	conda search beautifulsoup

	conda create -n myEnv numpy
	source activate myEnv      /OSX,Linux
	activate myEnv		   /Windows

	conda env export > envrionment.yaml
	conda env create -f environment.yaml
	conda env list
	conda env remove -n myEnv
	```
	(when sharing your code, it is good practice to create environment.yaml file)

* [Jupyter Notebook](http://jupyter.org/) Notebooks are a form of "literate programming ".

	```
	conda install jupyter notebook
	```

	**Keyboard shortcuts** 
	* _Enter/Return_ - edit mode  
	* _Enter+Shift_  -> next cell
	* _h_ - Help menu
	* _A/B_ - new cell
	* _Y_ - Markdown to Cell
	* _M_ - Code to Markdown
	* _L_ - line numbers 
	* _DD_ - deleting cell


*[FloydHub] Useful commands are : 
	* floyd -cli 
	* floyd login
	* floyd init <name>
	* floyd run --gpu --env tensorflow --data asdkfasd --mode jupyter
		(Make sure unnecessary data files are not there locally )
	* floyd status
	* floyd stop id/name
## Projects 

**Project 1. DLND Your first neural network**

A neural network for  _Bike-Sharing Company_. The system predicts, how many bikes they need.
```
conda env create -f dlnd.yaml
```
MindMap:
- Real world examples of Deep Learning
- Types of Model (Supervised, Unsupervised, ReinforcementLearning), Dependent and Independent Variables
- What is Linear regression and what is logistic regression. take e.g. as Univeristy Entrance problem
- Neural Networks and types of Perceptrons
- Gradient Descent and Maths with entire dataset. How error minimized here, multivariate calculus, partial derivatives, learning rate, squared-mean error ?
- Multilayer Perceptrons and sigmoid function
- BackPropagation, Explain?
		
**Project 2. Image Classification**

MindMap:
- Model Evaluation and Validation 
- How to create a test set for your models.
- How to use confusion matrices to evaluate false positives, and false negatives.
- How to measure accuracy and other model metrics.
- How to evaluate regression.
- How to detect whether you are overfitting or underfitting based on the complexity of your model.
- How to use cross validation to ensure your model is generalizable.


 Email: kumar.binit1992@gmail.com



# DeepLearningCodes

 These are the sample codes and assignment in Deep Learning 
 To run this files succesfully , You can get started with Anaconda, and Jupyter notebook

[Installating Anaconda] 
https://www.continuum.io/downloads.

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
(when sharing your code, it is good practice to create environment.yaml file)

[Jupyter Notebook]
Notebooks are a form of "literate programming ". It automatically renders with github.
There is also http://nbviewer.jupyter.org/ that renders the notebooks from your GitHub repo or from notebooks stored elsewhere.

conda install jupyter notebook
jupyter notebook - to start a notebook server 
Keyboard shortcuts 
Enter/Return - edit mode  
Enter+Shift  -> next cell
h- Help menu
A/B - new cell
Y - Markdown to Cell
M - Code to Markdown
L - line numbers 
DD - deleting cell
S

[GetStarted]

 Project 1. DLND Your first neural network
 	Creating a neural network to Bike-Sharing Company. The System predicts, how many bikes you need.
	conda env create -f dlnd.yaml
	
		MindMap:
		   1. Real world examples of Deep Learning
		   2. Types of Model (Supervised, Unsupervised, ReinforcementLearning), Dependent and Independent Variables
		   3. What is Linear regression and what is logistic regression. take e.g. as Univeristy Entrance problem
		   4. Neural Networks and types of Perceptrons
		   5. Gradient Descent and Maths with entire dataset. How error minimized here, multivariate calculus
		       , partial derivatives, learning rate, squared-mean error ?
		   6. Multilayer Perceptrons and sigmoid function
		   7. BackPropagation, Explain?
		
 Project 2. Image Classification
 
 		MindMap:
		   1. Model Evaluation and Validation
		   	How to create a test set for your models.
			How to use confusion matrices to evaluate false positives, and false negatives.
			How to measure accuracy and other model metrics.
			How to evaluate regression.
			How to detect whether you are overfitting or underfitting based on the complexity of your model.
			How to use cross validation to ensure your model is generalizable.
		   2. Sentiment Analysis
		   	
 Email: kumar.binit1992@gmail.com



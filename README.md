# DeepLearningCodes
 I have completed these projects as a part of Udacity's  [DeepLearning Foundation Nanodegree Programme](https://in.udacity.com/course/deep-learning-nanodegree-foundation--nd101)

## Projects : 

[**Project 1. DLND Your first neural network**](https://github.com/binit92/DeepLearningCodes/blob/master/dlnd-your-first-network/DLND%20Your%20first%20neural%20network.ipynb)
	
   My first neural-network to predict Bike Sharing Rides. Imagine yourself owning a bike sharing company like CycleHop. You want to predict how many bikes you need because if you have too few, you're losing money from potenial riders . If you have too many, you are wasting money on bikes that are just sitting around. So, you need to predict from historical data how many bikes you need in the near future.
   
	
[**Project 2. Image Classification**](https://github.com/binit92/DeepLearningCodes/blob/master/dlnd-image-classification/dlnd_image_classification.ipynb)

In this project, I have built a convolutional neural network with tensorflow. It recognize objects and images. Here, I am using [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html) which consists of 60000 images of ten different objects. This dataset is commonly used in computer vision research.
  

[**Project 3. TV Script Generation**](https://github.com/binit92/DeepLearningCodes/blob/master/dlnd-tv-script-generation/dlnd_tv_script_generation.ipynb)

Imagine you work for production company and your job is to write a script for one of their television shows. You could write the script manually or you could just use a computer to do it for you. In this project, I have generated a TV Script using recurrent neural network. I have trained the network on an existing script and use it to generate an original piece of writing.

[**Project 4. Language Translation**](https://github.com/binit92/DeepLearningCodes/blob/master/dlnd-language-translation/dlnd_language_translation.ipynb)

Language is the backbone of our civilisation. In early history, we used it exchange goods. Without written record of previous scientific discoveries, we could never accomplish greate events like travelling to space. We have accomplished a lot in a world where 13 of most common languages are natively spoken by less than 50% of the population. What would the world look like if we could all work together without a language barrier. This project is a pick in the realm of neural network machine translation. I have teach a model how to translate from one language to another 

[**Project 5. Face Generation**](https://github.com/binit92/DeepLearningCodes/blob/master/dlnd-face-generation/dlnd_face_generation.ipynb)

Imagine you work for a production company and your job is to design the character in a movie. You would usuall draw a bunch of different concepts before arriving at the final design. What if you have a neural network that could do it for you ? In this project, I have build Generative Adversial network that will generate new faces using celebrity images

## How to run these codes 
 To run this files succesfully , You can get started with Anaconda, and Jupyter notebook

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

 Email: kumar.binit1992@gmail.com

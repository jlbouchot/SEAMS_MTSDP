# [SEAMS School 2022 on Modern Trends in Machine Learning and Signal Processing](https://math.upd.edu.ph/seamsschoolmanila2022)
### 5-13 December 2022, Institute of Mathematics, University of the Philippines Diliman, Quezon City, Metro Manila, Philippines

![school banner](mtsdp.jpg)

## Compressed sensing and sparse approximation 
[Jean-Luc Bouchot](jlbouchot.github.io), Ph.D.

These lectures introduce the concept of compressed sensing, reviewing some ideas in sparse approximation and modeling and introducing basic iterative / greedy algorithms. 
Time permitting applications taken from numerical analysis and biology are presented. 

Topics include 
* Sparse phenomenon 
* L1 min is sparse
* Basis pursuit and the null space property 
* Coherence 
* Solving the quadratic bottleneck: RIP and random matrices 
* Greedy algorithms 

## Hands on sessions

### Accessing the data

Before getting started, make sure you have all the packages and resources available: 

'''git clone https://github.com/jlbouchot/SEAMS_MTSDP/'''

Unix (Linux/Mac) users should be fine going forward. 
Windows users should have access to an anaconda distribution. If not, either download anaconda or download any python distribution of your choice. 

### Setting up your virtual environment

Whilst not mandatory, virtual environments allow to not pollute various working projects. 
Some compatibility issues may arise by not containerising your packages. 

'''pip install virtualenv'''

We start with creating a venv. The rest assumes you are already **in** your working folder. 


virtualenv CompSensVEnv 

This creates a local repository names CompSensVEnv which will contain all the important links for the working environment which will be used in this hands on sessions. 
The environment is created through 

'''source CompSensVEnv/bin/activate''' in a Unix machine

or 

'''CompSensVEnv\Scripts\activate''' in a windows machine

From now on, everything you install will be locally to your environment and will not impact your main python distribution nor any other virtual environment you may have for other projects. 
This repository contains a file names '''requirements.txt''' which can be used to tell python what packages you are about to use. 
Let's make sure we have everything. 

'''pip install -r requirements.txt'''

You now see all the packages being downloaded, if they've never been downloaded before, or being linked if they already existed. 

You may now start your own jupyter server locally 

'''jupyter notebook''' 

### Available notebooks

You are given XXX notebooks to work out. They should be self contained, in the sense that most of the exercises are clearly detailed in the codeless cells.

[notebooks/IterThresholding](Soft/Hard Iterative Thresholding)

[notebooks/HTP.ipynb](Hard Thresholding Pursuit)

[slides/]
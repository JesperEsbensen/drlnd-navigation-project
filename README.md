# Banana Hunter

---
Created by Jesper Højmark Esbensen, 2018-08-31.<br>
<br>

This note book will create and train an agent to collect yellow bananas in the Unity Machine Learning environment Banana. The solution is based on the general deep reenforcement learning agent supplied in the cource [Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893).

![Banana Environment](https://github.com/JesperEsbensen/drlnd-navigation-project/blob/master/banana-env.png)

The environment is a square where yellow and blue bananas are dropping out of the sky. The agent is giving directions to at wagon that moves around in the square and collects bananas. Yellow bananas are rewarded with 1 point and blue bananas with -1. The task is to collect at least 13 points in averge over 100 episodes. An episode is 1000 steps in the environment.<br>


### 1. Installation instructions

The banana hunter is a python, pyTorch agent living in a Unity Environment. The agent is run from a jupyter notebook. Therefore you will need some setup before you can run the agent.

You will need to install python 3.6 and a few packages. One popular way to install python is through Anaconda. A python/R environment. To install this follow the instructions on: https://www.anaconda.com/distribution/.

Create an python environment using the "Create" button and select the python 3.6 version. Start a terminal for the environment and install jupyter.

Install jupyter in the environment. 

    python3 -m pip install --upgrade pip
    python3 -m pip install jupyter
   
or reference jupyters home page if you have problems: http://jupyter.org/install

The agent is bulid using Facebook's pyTorch. To install run the followin commands.

    conda install pytorch -c pytorch 
    pip3 install torchvision
    
or reference pyTorch's home page if you have problems: https://pytorch.org/

The environment is build on Unitys ML-agents modul. To run these you will need TensorFlow:

    pip install tensorflow==1.7.1

or reference TensorFlow's home page if you have problems: https://www.tensorflow.org/

Then install the ML-agenst from Unity.
Clone the repository: git clone https://github.com/Unity-Technologies/ml-agents.git
find and change to the directory: ml-agents/python and install the ml-agenst with:

    pip install .

or reference this page if you have problems: https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation-Windows.md


### 2. Clone the "Banana Hunter" project

To download this repository and run the banana hunter agent on your machine clone this github repository with the following command:

git clone https://github.com/


### 3. Train the agent

When you have installed all above packages and cloned the repository to your machine you can open and run the jupyter notebook Report.ipynb.

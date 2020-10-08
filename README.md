# CHAT-BOT-Rule-Based-One_and_Two
This part contains two chat bots which are all rule based.

## What the project does
This project shows a process in details on how to build two kinds of simple chat bot (rule-based)

## Why the project is useful
The code and theory are all at a beginning level, which is learner-friendly. By following this project, you can get familiar with
the usage of NLTK, building different environments in Anaconda and also setting up different kernels in Jupyter notebook.

## How users can get started with the project
These two chat bots in this project are all based on NLTK, however, before importing the NLTK, one problem must be solved, That is 
build a new environment in Anaconda and then match it with the relevant Kernel in the Jupyter notebook.
Here we usually do all these commands in the terminal such as the `Anaconda Prompt`

Here I'm going to show the process of matching envs&kernels and installing NLTK，

### 1. Open the Anaconda Prompt 
### 2. Build a new environment in Anaconda
```
conda create -n nlp222 python=3.5  # here I use "nlp222" as an example of the name
```
### 3. install ipykernel
```
conda install ipykernel # ipykernel is the key to make sure various linraries can update at the same time.
```
### 4. install ipykernel in Anaconda new env and then activate it
```
conda install -m nlp22 ipykernel
activate nlp22
```
### 5. put the activates kernel into jupyter notebook
```
python -m ipykernel install --user --name nlp22 --display -name nlp222
```
Here the `--name nlp22` is the env which we want to write into, and `--display -name nlp22 ` is the
name that will be shown in the Jupyter notebook.
### 6. import NLTK
Usually we have different methods to install NLTK, in Jupyter or in Anaconda
In Jupyter
```
pip install nltk
```
In Anaconda
```
conda install -c anaconda nltk  # -c means the channel
```


## Who maintains and contributes to the project

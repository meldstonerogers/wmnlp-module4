# WMNLP, Module 4 Project 
Melissa Stone Rogers, November 14, 2024


## Introduction
Professional project using Jupyter Lab, python, and spaCy to access web-hosted APIs to extract information from JSON responses. This project was created via a template of a repository provided by Northwest Missouri State University's School of Computer Science and Information Systems. 
Commands were used on a Mac machine running zsh.  

# Requests, JSON, and basic NLP with spaCy

Complete the tasks in the Python Notebook in this repository.
To be submitted for credit, all changes must be committed and pushed to this repository (do not create your own repository unless instructed to on the course website).

## Rubric

* (Question 1) Lyrics printed: 1 pt
* (Question 1) File created and submitted with notebook: 1 pt
* (Question 2) Correct polarity reported: 1 pt
* (Question 2) Question answered thoughtfully: 1 pt
* (Question 3) Function defined as specified: 1 pt
* (Question 3) Song lyrics retrieved and stored in separate files (0.5 pts/song): 2 pts
* (Question 4) Polarity scores printed (with appropriate label containing song title, .25 pts/song): 1 pt
* (Question 4) Questions answered thoughtfully: 2 pts


## How to Install and Run the Project
Create project repository in Github and clone to your machine.

```
git clone project.url
```
Verify Python version of Python 3
```
python3 --version

```
```
python3 -m venv venv
source venv/bin/activate
```

Install project dependencies dependent on your machine  
```
pip install jupyterlab 
pip install -U pip setuptools wheel
pip install -U spacy
python -m spacy download en_core_web_sm
pip install spacytextblob
```
Create requirements.txt in the root project folder. 
```
touch requirements.txt
```

## Freeze Dependencies 
```
python3 -m pip freeze > requirements.txt
```

## Add .gitignore File
Add .gitignore file to the root project folder if not already completed within repository creation in GitHub.
```
touch .gitignore
```
Add the following to your .gitignore file: 
- .venv/
- .vscode/
- .ipynb_checkpoints/

## Initial Project Save
```
git add .
git commit -m "initial"                         
git push origin main
```
### Start and Complete Project 
Follow instructions within the requests-json-nlp notebook file. 

## Complete Your Project
Save your project and push back to your repository. 
```
git add .
git commit -m "final"                         
git push origin main
```

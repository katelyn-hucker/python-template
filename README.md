# Python-Template
Mini-Project 1 

Fall 2023 IDS 706 Data Engineering

Katelyn Hucker (kh509)

This includes a Makefile, requirements.txt, .devcontainer, .gitignore, GitHubActions, and Readme.

The goal of this is to have a template that can be used in further projects for the data engineering class. This template includes all the necessary components needed in next development projects. 


# Makefile
-------------------------
Most of the makefile steps are actually commented out because this would cause errors as there are no .py files being used or pushed in the workflow. 

# requirements.txt
-------------------------
The requirements.txt file contains all the packages that we want to use in the system. The template contains all the packages that would be of use in any system. This includes pytest, ruff linter, a formatter, etc. 

# .devcontainer
-------------------------
The .devcontainer folder contains the Dockerfile and associated .json file. This runs the development project. 

# Github Actions
-------------------------
The github actions folder contains a .yml file which runs all needed actions for branches. It lints, formats, tests, deploys, and will run anything that is needed in the future. 

# .gitignore
-------------------------
The gitignore file is a base file that gets rid of any 'clutter' formed by pushing, pulling, and opening git files. 


# Discussion

All these files can be 'run' as a template, however, there is no point or output really. This template once added to a repository with a script and test cases shows its full functionality. 
When you run this template it just installs the packages and does the processes in the Makefile.


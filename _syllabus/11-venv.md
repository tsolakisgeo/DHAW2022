---
class: 11
day: Monday, October 24
title: Virtual Enviroments
tags: 
---

## Assignment due: 
- TBD 
- TBD 

## Before Class 
- TBD 
- TBD 

## Reading 
- TBD 
- TBD 

## Familiarize yourself with: 
- TBD 
- TBD 

## Notes 

#### Create a Virtual Environment
| Instructions | Commands |
|:-|:-|
|<img width=250/>|<img width=400/>|
|Open terminal|__Windows__ <br /> Windows+R. Type "CMD" <br /><br /> __Mac__ <br /> In applications, search for “Terminal” |
|Recommendation: Place it in a directory by itself. Even better: Create a directory for your project e.g., “myawesomeproject” and create a subdirectory venv. Don't put anything inside the venv subdirectory| `mkdir myawesomeproject` <br /> `mkdir myawesomeproject/venv`|
|Python is running the module venv and creates a subdirectory with the virtual environment|__Windows__ <br /> `python -m venv myawesomeproject\venv` <br /><br /> __Mac__ <br /> `python3 -m venv myawesomeproject/venv` |
|In order to activate the virtual environment, run the respective command|__Windows__ <br /> `myawesomeproject\venv\Scripts\activate.bat` <br /><br /> __Mac__ <br /> `source myawesomeproject/venv/bin/activate`|
|If you want to install a package, e.g. `requests`|`pip install requests`|
|Take the output and put it in a requirements.txt file|`pip freeze` <br /> `pip freeze > requirements.txt` <br /> `cat requirements.txt`|
|Let’s deactivate the environment...|`deactivate`|
|  ... and delete the directory |__Windows__ <br /> `rmdir myawesomeproject /s` <br /><br /> __Mac__ <br /> `rm -rf myawesomeproject/`|
|If you want to create a env with the same packages|__Windows__ <br /> `python -m venv myawesomeproject\venv` <br /> `myawesomeproject\venv\Scripts\activate.bat` <br /> `pip install -r requirements.txt` <br /><br /> __Mac__ <br /> `python3 -m venv myawesomeproject/venv` <br /> `source myawesomeproject/venv/bin/activate` <br /> `pip install -r requirements.txt`|

#### Create a Virtual Environment for Jupyter Notebook
- conda create -n myenv
- conda create -n myenv python=3.6
- conda activate myenv
- conda env remove -n myenv

- pip install --user ipykernel
- conda install -c anaconda ipykernel
- python -m ipykernel install --user --name=venv
- jupyter notebook

#### Managing Virtual Environments ([Workflow](https://twitter.com/paregorios/status/1578455947621515264) by Dr. Tom Elliott)

# Introduction

This is a jupyter notebook I created because most of the examples around machine learning are not documented in place. In my personal opinion those example are hard to follow. 

You end up having a tutorial and python code in separate places. This example jupyter notebook on the otherhand has all all the code and its explanation in one place allowing the reader to run live examples.

# Setting up the environment

To setup the environment to run this notebook, follow the instructions below 

1) Install python 3 and make sure PYTHONHOME variable points to where python is installed

2) Also make sure PATH variable includes PYTHONHOME

on unix
```
export PATH=$PATH:$PYTHONHOME
```
on windows
```
PATH=%PATH%;%PYTHONHOME%
```

3) Upgrade pip

```
pip3 install --upgrade pip
```

4) Install virtual environment in the directory where this repo is checked out
```
pip3 install --user --upgrade virtualenv
virtualenv venv
```

5) Activate the environment
```
venv/Scripts/activate
``` 

6) Upgrade pip in your newly activated virtual environment 
```
pip install --upgrade pip
```

7) Install jupyter and all dependency libraries
```
pip install --upgrade jupyter matplotlib numpy pandas scipy scikit-learn
```

alternatively you can also run

```
pip install -r requirements.txt
```

8) run Jupyter server
```
jupyter notebook
```

Note: If you are editing some of the text files on Windows please use dos2unix to checkin the files

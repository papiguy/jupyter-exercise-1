1) Install python 3 and make sure PYTHONHOME variable points to where python is installed
2) Also make sure PATH variable includes PYTHONHOME

on unix

export PATH=$PATH:$PYTHONHOME

on windows

PATH=%PATH%;%PYTHONHOME%

3) upgrade pip
```
pip3 install --upgrade pip
```

4) install virtual environment in the directory where this repo is checked out
```
pip3 install --user --upgrade virtualenv
virtualenv venv
```

5) activate the environment
```
venv/Scripts/activate
``` 

6) upgrade pip in your newly activated virtual environment 
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

8) run jupyter server
```
jupyter notebook
```

Note: If you are editing some of the text files on Windows please use dos2unix to checkin the files

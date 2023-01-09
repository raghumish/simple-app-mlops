Create env
```conda create -n wineq python=3.7 -y```

Activate env
```conda activate wineq```

Create requirement.txt
Install the requirements
```pip install -r requirement.txt```

Download data for wine data quality
winequality.csv

Initialize all the files
```git init```
```dvc init```
```dvc add data_given/winequality.csv```

Get ready to commit to git
```git add .```
```git commit -m "first commit"```

First time use these commands
```git remote add origin https://github.com/raghumish/simple-app-mlops.git```

```git branch -M main```

For periodic updates/ one-liner update use the git add . Then run the git push

Choose token as password for push origin command
```git push -u origin main```

To commit one-liner update
```git add . && git commit -m "update Readme.md"```

To run the pipeline and checking scores
```dvc repro```
```dvc metrics show```
```dvc metrics diff```

To install tox for test automation, create a dir 'tests'

```touch tests/conftest.py tests/test_config.py tests/__init__.py```

```pytest -v```

To capture setup related to the project, create setup file
```touch setup.py```

```pip install -e .```

The folder src.egg-info will have all the packages for the project.
This can be used with an import command on any other directory or env.
Create setup file for distribution using command and share the .tar.gz file

```python setup.py sdist bdist_wheel```

tox command
```tox```

for rebuilding -
```tox -r```

pytest command
```pytest -v```

setup commands -
```pip install -e .```

build your own package commands-
```python setup.py sdist bdist_wheel```

Follow pep8 styling guide for python. 
Use flake8 to check if the code does not follow the style guide.


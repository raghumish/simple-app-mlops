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

For periodic updates/ one-liner update use the git add .

Then run the git push

Choose token as password for push origin command

```git push -u origin main```

To commit one-liner update

```git add . && git commit -m "update Readme.md"```



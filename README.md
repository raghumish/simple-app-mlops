Create env
conda create -n wineq python=3.7 -y

Activate env
conda activate wineq

Create requirement.txt

Install the requirements
pip install -r requirement.txt

Download data for spam filtering
winequality.csv

git init

dvc init

dvc add data_given/winequality.csv

git add .

git commit -m "first commit"

one-liner update
git add . && git commit -m "update Readme.md"

git remote add origin https://github.com/raghumish/simple-app-mlops.git

git branch -M main

git push -u origin main

Choose token as password for push origin command


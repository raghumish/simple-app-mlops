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

git add . && git commit -m "update Readme.md"
create env

'''bash
conda create -n wineq python=3.7 -y
'''

activate env
'''bash
conda activate wineq
'''

created a req file
'''bash

'''

install the requirement
'''bash
pip install -r requirements.txt
'''

git init

dvc init
dvc add data_given/winequality.csv
git add .

git commit -m "message"

git remote add origin https://github.com/khitishsahu/simple-dvc-demo.git
git branch -M main
git push origin main

git add . && git commit -m "message" && git push origin main
create env

'''bash
python -m venv "Virtual env name"  
conda create -n wineq python=3.7 -y
'''

activate env
'''bash
conda activate wineq
source test/bin/activate
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

tox 
'''bash
tox
'''

for rebuilding
'''bash
tox -r
'''

pytest command
'''bash
pytest -v
'''

setup command
pip install -e .


build your own package
'''bash
python setup.py sdist bdist_wheel
'''

create an environment
``` conda prompt
conda create -n wineq -y
```

activate environment
``` conda prompt
conda activate wineq
```
created the requirements.txt

install requirements.txt
``` conda prompt
pip install -r requirements.txt
```

download the data from 

https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec

initialize the git
``` conda prompt
git init
```
initialize the dvc
``` conda prompt
dvc init
```
add given data to the dvc
``` conda prompt
dvc add data_given/winequality.csv
```
add all files to git
``` conda prompt
git add .
```
first commit to the git
``` conda prompt
git commit -m "first commit"
```
one lineer command to add and commit to dvc
``` conda prompt
git add . && git commit -m "update Readme.md"
```
adding remote git repo
``` conda prompt
git remote add origin https://github.com/shubhammodi/simple-dvc-demo.git
```
selecting/creating main branch on git
``` conda prompt
git branch -M main
```
pushing data to main branch
``` conda prompt
git push -u origin main
```
checking the history of commands in windows os
``` conda prompt
doskey /History
```

tox to run the test cases
``` conda prompt
tox
```

tox to run the test cases with rebuild env
``` conda prompt
tox -r
```

pytest to run the test cases
``` conda prompt
pytest -v
```

setup commands -
``` conda prompt
pip install -e .
```

build your own package commands -
``` conda prompt
python setup.py sdist bdist_wheel
```
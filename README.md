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

git init

dvc init

dvc add data_given/winequality.csv

git add .

git commit -m "first commit"

git add . && git commit -m "update Readme.md"
git remote add origin https://github.com/shubhammodi/simple-dvc-demo.git
git branch -M main
git push -u origin main
doskey /History
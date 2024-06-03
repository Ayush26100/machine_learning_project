# machine_learning_project
Machine Learning Project

Creating conda enviorment
```
conda create -p venv python==3.7 -y
```

To activate enviorment....
```
conda activate venv/
```

```
pip install -r -requirements.txt
```

Note : To ignore a file in git we can write those file name in .gitignore

To stage filein git
```
git add <file name>
```
To commit in git
```
git commit -m "message"
```
to push
```
git push origin <branch name>
```

Setup IN GITHUB requires parameter

EMAIL : <HEROKU_EMAIL>
HEROKU_SECRET: <HEROKU_SECRET>
HEROKU_APP_NAME : <HEROKU_APP_NAME>

Build Docker Image

```
docker build -t <image_name>:<tagname> .

Note: Image namefor docker must be in lowercase


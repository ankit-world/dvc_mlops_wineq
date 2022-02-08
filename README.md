create new env

```bash
conda create new -n env python=3.7 -y
```

activate env

```bash
conda activate env
```

create requirements.txt file and install it

```bash
pip install -r requirements.txt
```

download the data from

```bash
https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing
```

```bash
git init
```

```bash
dvc init
```

```bash
dvc add data_given/winequality.csv
```

```bash
git add .
```

```bash
git commit -m "first commit"
```

```bash
git add .  && git commit -m "update README.md"
```

```bash
git remote add origin https://github.com/ankit-world/dvc_mlops_wineq.git
```

```bash
git branch -M main
```

```bash
git push -u origin main
```

```bash
git add .  && git commit -m " README.md updated" && git push origin main
```


tox command
```bash
tox
```

for rebuilding
```bash
tox -r
```

pytest command
```bash
pytest -v
```

setup commands
```bash
pip install -e.
```

build your own package
```bash
python setup.py install sdist bdist_wheel
```

create an artifacts folder

mlflow server command
```bash
mlflow server \
    --backend-store-uri sqlite:///mlflow.db \
    --default-artifact-root ./artifacts \
    --host 127.0.0.1 -p 5000
```
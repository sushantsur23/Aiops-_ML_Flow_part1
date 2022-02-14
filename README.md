# Aiops-_ML_Flow_part1

#Commands
```bash
python runs.py

mlflow run .        (if we are in the current directory but generally it gives error)

mlflow run . --no-conda     (if we are in the same environment and doe not create another conda env)

mlflow run https://github.com/sushantsur23/Aiops-_ML_Flow_part1.git -P param1=6 -P param2=7 --no-conda
(use above code to run from github directly, if you get error try to publish on master node of Github)

mlflow ui


```
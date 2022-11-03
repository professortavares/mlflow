# mlflow
 Just an example of using MLFlow

## Dev.:

1. Create virtual env:

```
$ python -m venv mlflow_env
```

2. Activate virtual env:

```
$ . mlflow_env/bin/activate
```

If you want to deactivate:

```
$ deactivate
```

4. Install requirements:

```
$ pip install -r requirements.txt
```

And then...

```
$ pip install -e .
```


or update (if you want to add some package):

```
pip install --upgrade --force-reinstall -r requirements.txt
```


mlflow server  --backend-store-uri sqlite:///mlflow.db --default-artifact-root ./mlruns
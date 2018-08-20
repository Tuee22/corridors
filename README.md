This is designed to be used within a pipenv environment.

```
pipenv install
```
or 
```
pipenv install --dev
```

Then build the CPP bindings via:

```
pipenv run python setup.py build_ext --inplace
```

Run the GUI:

```
pipenv run python -m corridors
```

Interact with the code directly:

```
pipenv install --dev
pipenv run ipython
```
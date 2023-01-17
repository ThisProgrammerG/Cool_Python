# Cool_Python

## reorder-python-imports
Requires:
```
pip install reorder-python-imports
```
Then, using the current working directory, in PowerShell type the following command:
```
Get-ChildItem -Path . -Directory -Exclude "venv" | foreach-object {Get-ChildItem $_.FullName -Filter *.py -Recurse} | foreach-object { & reorder-python-imports --py311-plus $_.FullName }
```

## Black
Requires:
```
pip install black
```
Run in PowerShell:
```
black .
```

## Speed up python:
```
https://github.com/zq1997/RegCPython
```

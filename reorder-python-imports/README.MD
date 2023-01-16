# reorder-python-imports
Requires:
```
pip install reorder-python-imports
```
Then, using the current working directory, in PowerShell type the following command:
```
Get-ChildItem -Path . -Filter *.py -Recurse | foreach-object { & reorder-python-imports --py311-plus $_.FullName }
```

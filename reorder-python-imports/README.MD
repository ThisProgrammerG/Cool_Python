# reorder-python-imports
Requires:
```
pip install reorder-python-imports
```
Then type into PowerShell with the following command using the current working directory:
```
Get-ChildItem -Path . -Filter *.py -Recurse | foreach-object { & reorder-python-imports --py311-plus $_.FullName }
```

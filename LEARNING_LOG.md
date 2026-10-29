# My notes and definitions

## venv

### .venv: virtual environment
### setup- py -m venv .venv

- if it does not load up becasue of disabling:  
- Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

- .venv\Scripts\Activate.ps1

## why venv?
### isolate python environment from global environment. keep everything containerized. Keep your system cleaned and prevent conflicts between potentially different libraries or python versions

# running where.exe python
## shows location: C:\Users\brand\AppData\Local\Microsoft\WindowsApps\python.exe

# libraries installed
- pandas
- requests
- jupyter

## requests
### send HTTP requests and interact with web resources
### fetch data or trigger actions on third party servers

- GET
- POST
- PUT
- DELETE
- PATCH

### you can download page contents/ intefaces with security keys using minmal self-documenting code

## requesting an API Key
### authenticate and identify the specific application or project making request to external service

### needed to increase data limits to a bigger quota. it keeps servers from being overriden by traffic

### need to import os because it reads the .evn which holds the API key

## watch outs
### shadowing: reusing name and hiding what it refers to


# Keys in FAERS report
## print(len(reports),reports[0].keys())

### one report and the keys are top level fields in one FAERS report.
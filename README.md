# Release Audit

Small Python program for displaying support-ticket information.

## Requirements
- Python 3.12 or newer
- Git
- project dependencies from ```requirements.txt```

## Setup
Run the following:  
```git clone https://github.com/salocin24/CPS310-ICA08-DevOps.git```  
```python -m venv .venv```  
```.\.venv\Scripts\Activate.ps1```  
```python -m pip install -r requirements.txt```

## Configuration
Project settings are stored in ```config.json```
```"data_file"``` points to where your summary is pulling data from
```"report_title"``` is the name of your report
```"high_priority_threshold"``` determines at what point an item is high priority

## Run

```text
python release_audit.py
```

## Running the Tests
```python -m pytest -v```

## Running verification
```.\verify.ps1```

## Release-Readiness Statement
Now that the project has explicit configuration files, easy powershell scripts for dependency installs and file verification, getting this repository up and running on any machine is much easier.

More setup information will be added later.

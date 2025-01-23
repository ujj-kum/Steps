### 1. Virtualenv creation
python3 -m venv envName
##### In desired folder
python3 -m venv /path/to/directory/env_name

### Activate in PowerShell/VS Code
##### Bypass Powershell Restriction
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
### Activate environment
 .\envName\Scripts\activate

### 2. Activate virtualenv 
source env/bin/activate  

### 3. Check Environment
which python

### 4. Install dependency
pip install pandas  
##### All at once
pip install -r requirements.txt

### 5. Deactivate when done
deactivate

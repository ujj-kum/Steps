### 1. Create virtual environment using conda
conda create --name myEnvName python=3.10              # C:\Users\<username>\.conda\envs

#### In desired location
a. conda create --prefix /custom/path/to/env python=3.10

b. conda create --prefix ./myEnvName python=3.10       # In the current working directory



conda activate myEnvName

pip install -r requirements.txt

### 2. Virtualenv creation 
python3 -m venv envName
##### In desired folder
python3 -m venv /path/to/directory/env_name

### Activate in PowerShell/VS Code
##### Bypass Powershell Restriction
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
### Activate environment
 .\envName\Scripts\activate (For Powershell)
 source envName/Scripts/activate (For Git Bash or Linux Based Cmd)

### For .iypnb files
install jupyter and ipykernel in the environment (from requirements.txt preferred)

python -m ipykernel install --user --name=envName --display-name "Python (myenv)"


### 3. Activate virtualenv 
source env/bin/activate  

### 3. Check Environment
which python

### 4. Install dependency
pip install pandas  
##### All at once
pip install -r requirements.txt

### 5. Deactivate when done
deactivate

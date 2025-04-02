# Rasa Tutorials
### Install Python
`Rasa` requires python 3.8++



1. Check python version
```bash
python --version  # check to the python version
# Python 3.8++
```
> 👉 If you have Python 3.8++ installed, skip to [Install Rasa](#install-rasa).
2. Install python 3.8++ [Python downloads](https://www.python.org/downloads/)
3. Create Virtual enviorment
```bash
python -m venv rasa_env
source rasa_env/bin/activate  # macOS/Linux
rasa_env\Scripts\activate  # Windows
```



### Install Rasa
1. Install Rasa
```bash
pip install rasa
```
2. Check Rasa
```bash
rasa --version
```



### Create Rasa Project
1. Initialize Rasa
```bash
rasa init
```



### Run Rasa
1. Train Rasa
```bash
rasa train
```
2. Run Rasa Action Sercer
```bash
rasa run actions
```
3. Run Rasa Shell
```bash
rasa shell
```
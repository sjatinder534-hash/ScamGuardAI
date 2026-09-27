# ScamGuardAI
This is sample readme file

## Commands to be followed

### GIT Commands
```
git status
git add . / git add <fielname>
git commit -m "message"
git push origin main
git pull
```

### Environement management
```
conda create -n <env_name> python=3.11 -y
conda activate <env_name>
conda deactivate
pip install -r requirements.txt
```

### UV commands
```
uv venv <env_name> --python 3.11
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
uv pip install -r requirements.txt
```

### Project Structure
ScamGuardAI
- experiments
    - `workflow.ipynb`
- llm
    - `__init__.py`
- pipeline
    - `__init__.py`
- streamlit'
    -`__init__.py`
`__init__.py`
requirements.txt
utils.py
main.py

__init__.py tells Python that a directory should be treated as a Python package. It can also contain package initialization code.
```
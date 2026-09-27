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
| Conda / pip                                 | `uv`                                 |
| ------------------------------------------- | ------------------------------------ |
| `conda create -n <env_name> python=3.11 -y` | `uv venv <env_name> --python 3.11`   |
| `conda activate <env_name>`                 | `.\<env_name>\Scripts\Activate.ps1`  |
| `conda deactivate`                          | `deactivate`                         |
| `pip install -r requirements.txt`           | `uv pip install -r requirements.txt` |

```
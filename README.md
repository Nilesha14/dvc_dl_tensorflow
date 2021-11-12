# DVC - DL - TF - AIOPS

download data --> [source](https://drive.google.com/drive/u/0/folders/1tz4IOoJKdi999IRdqJY04VOifyllRzj1)

## commands -

### create new env
```bash
conda create --prefix ./env python=3.7 -y
```

### conda activate env
```bash
conda activate ./env
```

### init DVC
```bash
git init
dvc init
```

### create empty files
```bash
mkdir -p src/utils config
touch src/__init__.py src/utils/__init__.py params.yaml dvc.yaml config/config.yaml src/stage_01_load_save.py src/utils/all_utils.py setup.py .gitignore

```

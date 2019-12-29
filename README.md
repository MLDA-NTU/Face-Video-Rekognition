# GTD Service

## Requirements

- `python=3.5.2`
- `MySQL`
- `virutalvenv`
- `git`

## Installation

```bash
pip install -r requirements.txt # ensure that you are using virtualvenv and python 3
```

## Run Server

```bash
export DATABASE_URI=mysql+pymysql://root:root@127.0.0.1:3306/gtd # get your mysql url, optional
export FLASK_ENV=development # dev mode
export DEBUG=True # dev mode
python run.py # available at 127.0.0.1:5000
```

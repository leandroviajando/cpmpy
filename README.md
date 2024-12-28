# CPMpy

## Setup

```bash
pyenv local 3.11.9
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements-dev.txt
pip install -r requirements.txt
```

### Generate PDFs

```bash
jupyter nbconvert --to pdf *.ipynb
```

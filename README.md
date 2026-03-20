# DJANGO_EXAM_CARD_SYSTEM

## Virtual Environment Setup Instructions
### 1. Create a virtual environment
It's recommended to keep all you virtual environments in one place (e.g.,a  .virtualenvs directory your home folder).
```bash
python3 -m venv ~/.virtualenvs/examcardsys
```

### 2. Activate the virtual environment
```bash
source ~/.virtualenvs/examcardsys/bin/activate
```

### 3. Deactivate the Virtual Environment
To deactivate the virtual environment, simply run:
```bash
deactivate
```

## Install Django
### 1. Installation
Enter the command below to install django
```bash
python3 -m pip install Django
```
### 2. Verifying
To verify that Django can be seen by Python, type ***python*** from your shell. Then at the Python prompt, try to import Django:

```bash
>>> import django
>>> print(django.get_version())
6.0.3
```

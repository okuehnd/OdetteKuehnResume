# Odette Kuehn Resume
## Django Individual Assignment

- Uses Django templates, HTML, CSS

## File Structure
```
odkueResume #Django Project
│──odkueResume #Django App
  │──odkueResume #main App files
  │──pages #resume page
    │──migrations
    │──static/css # contains style page and jpegs
    │──templates #html file for resume
│──.gitignore
│──requirements.txt

```

## Clone Repository
```
git clone https://github.com/okuehnd/OdetteKuehnResume
cd OdetteKuehnResume
```

## Create and Activate Virtual Environment
```
python -m venv venv
```
PowerShell
```
venv\Scripts\activate
```
Mac/Linux
```
source venv/bin/activate
```
## Install Dependencies
```
pip install -r requirements.txt
```
## Change to app directory
```
cd odkueResume
```
## Apply Migrations
```
python manage.py migrate
```

## Run Server
```
python manage.py runserver
```
## Visit: __http://127.0.0.1:8000/__ in your browser








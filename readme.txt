in gitignore file
  don't include venv folder
  only include scripts
  ref --> https://www.youtube.com/watch?v=APOPm01BVrk

to save to requirements file
  pip freeze > requirements.txt

to install from requirements file.
  pip install -r requirements.txt

to remove virtual environment
  rmdir venv /s

to add base libraries into virtual venv
  python -m venv venv --system-site-packages

to see only local libraries
  pip list --local

# django-test
Goal: reproducible example to test zed debugger

## create conda environment
conda env create -f environment.yml

## activate conda environment
conda activate django-test

## run django server
python manage.py runserver

## Notes
Zed seems to have heavy issues when having an active conda environment and asdf python plugin installed...

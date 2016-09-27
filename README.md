## Synopsis

Poll application using python3 and django 1.10


## Motivation


## Installation

Run the following commands:

```
git clone https://github.com/fdiazcaballero/poll-app-django.git

cd poll-app-django
 
virtualenv poll_dev

virtualenv poll_test

source poll_dev/bin/activate

pip3 install -r requirements/development.txt

deactivate

source poll_test/bin/activate

pip3 install -r requirements/testing.txt

```

Don't forget to include you poll_test and poll_dev folders in your .gitignore or exclude files, those folders do not need to be committed.


## API Reference


## Tests

From the dev environment activated run:

python manage.py runserver

In another console from the test environment run:

python functional_tests/*.py


## Contributors

Fernando Diaz Caballero


## License

Apache

# birthday-greetings-kata

## running tests

### I have pipenv

    pipenv install --dev
    pipenv run test

### I don't have pipenv

    python3 -m venv env
    source env/bin/activate
    pip install -r requirements.txt
    pytest

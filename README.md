# Flask-Api-Template

A simple Python application showing how to structure multiple APIs within Flask.

## Install

Installation is performed via Poetry

```
❯ poetry shell
... 
❯ poetry install
...
```

## Testing

Application testing is via Pytest

```
❯ poetry run pytest
=========================== test session starts ===========================
platform linux -- Python 3.11.4, pytest-7.4.2, pluggy-1.3.0
rootdir: /home/david/Code/flask-api-template
collected 9 items                                                         

tests/test_moonphase.py ..                                          [ 22%]
tests/test_solstice.py .                                            [ 33%]
tests/api/test_moon_api.py ....                                     [ 77%]
tests/api/test_sun_api.py ..                                        [100%]

============================ 9 passed in 0.14s ============================
```
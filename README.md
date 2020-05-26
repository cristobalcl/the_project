the_project
===========

Companion project for the article series:

* [How to start a Python project with Django in 2020](https://medium.com/@cristobalcl/how-to-start-a-python-project-with-django-in-2020-803122721b23?sk=f8989aec603e1e8d40ffc3d3dd7e4b50)
* [Set up tests, linters and type checking in Python projects in 2020](https://medium.com/@cristobalcl/set-up-tests-linters-and-type-checking-in-python-projects-in-2020-9cc1b1e2750d)

Dependencies
------------

* [pyenv](https://github.com/pyenv/pyenv#installation)
* [Poetry](https://python-poetry.org/docs/#installation)
* [nox](https://nox.thea.codes)

Setup
-----

```bash
pyenv install 3.8.2
```

After cloning the repo:

```bash
poetry run pre-commit install
```

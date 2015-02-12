# Python ORM Libraries Installed in a `virtualenv`

Maintainer: Colin Stephen

## About

This repository contains a full python virtualenv configured with a number of ORM libraries for testing/development:

* SQLObject
* SQLAlchemy
* Peewee
* PonyORM

**NOTE:** The environment is configured for _Windows only_. If you use Linux / OSX then come and speak to Colin during support hours or during a class.

## Usage

On the command line, ensure you `cd` in to your project directory first, in order for the following commands to work.

1. Clone this repository into your project directory using `git clone`
    * If it worked, you will now have a `venv` folder inside your project directory
2. To load the environment from the command line run `venv\Scripts\activate.bat`
    * If it worked, your command prompt will now show `(venv)` before the path
3. You can now run any of your Python files from the command line with `python <filename.py>`
    * Your Python file(s) will be able to use the ORM libraries included
    * Just import them as normal with `import sqlalchemy` or `from sqlalchemy import Column, Integer, String` etc...
4. To deactivate the virtualenv, simply close the command prompt window, or execute `venv\Scripts\deactivate.bat`

**NOTE:** If you want to be able to use the libraries included, then you need to run your Python scripts from the command line as described above. It will not work if you try to run the script from within IDLE.

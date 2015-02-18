# Python ORM Libraries Environment

Maintainer: Colin Stephen

**NOTE:** This environment is configured for _Windows only_. If you use Linux / OSX then come and speak to Colin during support hours or during a class for guidance.

## About

This repository contains a full Python [virtualenv](http://docs.python-guide.org/en/latest/dev/virtualenvs/) configured with a number of ORM libraries for testing/development. For a quick comparison of their APIs and links to specific documentation, see [Part 3 of the Python SQLAlchemy Tutorial](http://www.pythoncentral.io/sqlalchemy-vs-orms/).

The libraries included here are:

* SQLObject
* SQLAlchemy
* Peewee
* PonyORM

## Usage

1. Load up the SourceTree git client
1. Open the "Terminal" command line in SourceTree
1. `cd` in to your project directory (use `pwd` to show the current directory, `ls` to list current files, and `cd ..` to move up a level)
1. Clone this repository into your project directory using `git clone https://github.com/coventryuniversity/python-sql-libs.git venv`
    * If it worked, you will now have a `venv` folder inside your project directory
1. You can now run any of your Python files from the command line with `venv\Scripts\python.exe <filename.py>`
    * Your Python file(s) will be able to use the ORM libraries included
    * Just import them as normal with `import sqlalchemy` or `from sqlalchemy import Column, Integer, String` etc...

## IDLE and Other Editors

If you want to be able to use the libraries included here, then you need to run your Python scripts from the command line as described above. It will not work if you try to run the script from within IDLE or another editor. So, _edit_ your files in IDLE or another editor, but _run_ the file from the command line as above.

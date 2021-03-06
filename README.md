# Jupyter Export Watcher

## What does it do?
TL;DR: Importing Jupyter notebooks as modules.

This command watches the filesystem (recursively) for changes to \*.ipynb files, and when a change occurs, it exports those files to \*.py and removes whitespace from the names of the exported versions so they can be imported in Python as modules.

## Is it any good?
Yes.

## Installing Dependencies
- [Node.js](https://nodejs.org/en/)

- [Python](https://www.python.org/)

- [Jupytext](https://jupytext.readthedocs.io/en/latest/install.html)

- [Nodemon](https://github.com/remy/nodemon)

## Running
- Clone the repo and place it in the same parent directory your Jupyter notebooks reside in
- Command
```
$ python ./jupyter-export-watcher/app.py
```
# Medusa Clean Staging

This is a python script for Library staff at the University of Illinois at Urbana-Champaign to search for and optionally remove files and directories intended to be excluded from the Medusa Colletion Registry.

## Python 3

Python version 3 must be installed.

On Windows you can type "Python" in the Windows Search Bar.

On a Mac, you open a terminal and type 
```python --version```

If python version 3 is not installed on your system, work with Library IT to get it installed.

### Usage

Save the medusa-clean-staging.py file anywhere convenient.

On Windows open a command prompt (press Windows start and type cmd) or on a Mac open a terminal. Navigate to the directory where you saved the script file (or adjust the below commands for relative path).

```
python medusa-clean-staging.py
```
or
```
python medusa-clean-staging.py Drive:\path\to\staging\directory
```

The difference is that if you include the path to the staging directory, the program will use that. Otherwise, if you omit it, the program will prompt you for the path.
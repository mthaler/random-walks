# random-walks

Random Walks project from Python Crash Course

![alt text](screenshots/random_walks.jpg "Random Walks")

## Add Matplotlib package when using PyCharm

The Random Walks app requires the Matplotlib package to be installed.
If it is missing, PyCharm will show the following error:

![alt text](screenshots/missing_matplotlib_package.jpg "Missing Matplotlib package")

To add the package for the Random Walks app, move the cursor to *import matplotlib.pyplot as plt* and press *Alt-enter*. The following popup menu should be shown:

![alt text](screenshots/install_matplotlib_package.jpg "Install Matplotlib package")

To install the Matplotlib package, select *Install package matplotlib*. This only works when using a correctly configured virtual environment.

## Installing Matplotlib

To install Matplotlib for the current user, enter the following command at a terminal prompt:

```
$ python -m pip install --user matplotlib
```

To install Matplotlib globally on Debian based systems, do:

```
# apt-get install python3-matplotlib
```

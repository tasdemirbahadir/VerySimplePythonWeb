# VerySimplePythonWeb

The simplest & complete (with html layouts and test cases) version of a Python Dynamic Web Project. After following the setup instructions, you can start from scratch if you want to make an introduction to Python Web Projects.

## Getting Started

Clone/download project into a folder on your machine. After setting up the environment, your project will be ready to run.

### Prerequisities

Install python 2 on your machine (because this project is built with Python 2).

For windows: Go to https://www.python.org/downloads/windows/, download and install.

Make sure your environment variable is correct. Go My Computer-->Properties-->Advanced system settings-->Advanced-->Environment Variables At system variables, find variable 'PATH', add '[path_to_python]'. Mine is "C:\Program Files\Python".

Check if python is ready. Open cmd, Run command:
```
python
```
And you must see something like:
```
Python 2.7.10 (default, May 23 2015, 09:44:00) [MSC v.1500 64 bit (AMD
n32
Type "help", "copyright", "credits" or "license" for more information.
>>>
```
Type "quit()" and hit enter to exit from Python.

## Built With

* lpthw.web

Before running the web application, you must install some additional modules (scripts) for python.

* First, install "pip" Go to "https://pypi.python.org/pypi/pip", download file, unzip. Open a cmd with "run as administrator (otherwise the windows can block the installation)", change directory to the root of the downloaded file. Finally type "python setup.py install"

* Second, install "nose" Go to "https://pypi.python.org/pypi/nose/", downloa file, unzip. Open a cmd with "run as administrator (otherwise the windows can block the installation)", change directory to the root of the downloaded file. Finally type "python setup.py install"

* Third, install "lpthw.web" Go to "https://pypi.python.org/pypi/lpthw.web", download file, unzip. Open a cmd with "run as administrator (otherwise the windows can block the installation)", change directory to the root of the downloaded file. Finally type "python setup.py install"

Important Note!: Check if the environment variable for the python scripts is set. Go My Computer-->Properties-->Advanced system settings-->Advanced-->Environment Variables At system variables, find variable 'PATH', check the value and add the python scripts path if does not exist. My path is "C:\Program Files\Python\Scripts".

## Run

* Go to the root folder of the downloaded project with cmd. Type "python bin/app.py". If you got some errors, start from the very beginning again and check if you made any steps wrong. Also you can mail me in the case of needing help. After running the project, open a web browser and type "http://localhost:8080/" then hit enter. You must see a valid web page.

## Testing

* To run the test cases, go to the root folder of the project with cmd and type "nosetests". Because you have the python scripts folder path in your environment path variable, the system will recognize the command and run the created tests.

## Contributing

Any one is permitted to contribute the project.

## Versioning

* 1.0

## Authors

* **Bahadir Tasdemir** - *Owner* - [btasdemir.com](http://www.btasdemir.com)

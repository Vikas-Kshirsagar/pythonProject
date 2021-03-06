# pythonFlask
> This is the python code written to learn the basics of Python's flask microframework and Git commands from terminal .

## Getting Started

### Installation
**Copy project from gitHub repository**

This command will clone the repository folder on the current location of terminal.

```
git clone https://github.com/Vikas-Kshirsagar/pythonFlask.git 
```

### Install Python

Install python V3.0 or latest as flask provides good support for the python 3. Use pip to install python if needed.
Python 3 comes bundled with the venv module to create virtual environments. If you’re using a modern version of Python, you can continue with following,

```
python3 -m venv venv
```

On Windows:

```
py -3 -m venv venv
```

If you needed to install virtualenv because you are on an older version of Python, use the following command instead:

```
virtualenv venv
```

### Run these commands to activate environment
On Windows:
```
venv\Scripts\activate
```
### Install Flask

Within the activated environment, use the following command to install Flask:
```
pip install Flask
```
### Run these commands to start the project
```
* $env:FLASK_APP = "app.py"*
* set FLASK_ENV=development*
* python -m flask run*
```
### Start Debug mode in 
```
In Windows -->   $env:FLASK_DEBUG=1
In Ubuntu --> $env:FLASK_DEBUG=1
```

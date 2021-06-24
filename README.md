# Python Mentoring

## How to Start

**How to find `Terminal` on MacOS?**

`Command + Space` and then type `Terminal`


**How to get current Python version in Terminal?**
```bash
python --version
```

**How to install `pyenv` on MacOS?**
```bash
brew install pyenv
```

**How to install necessary Python version in `pyenv`?**
```bash
pyenv install <necessary python version> 
```
>`necessary python version` is something like that: `3.8.0`, `3.6.5`, `2.7.3`, etc


**How to install pyenv-virtualenv?**
```bash
brew install pyenv-virtualenv
```

**How to install virtualenv using `pyenv`?**
```bash
pyenv virtualenv <necessary python version> <virtualenv name>
```
>`necessary python version` is something like that: `3.8.0`, `3.6.5`, `2.7.3`, etc
>
>`virtualenv name` is any string, something like that: `test`, `pet_project`, `my_app`, etc.

>if you get this error:
```
Failed to activate virtualenv.

Perhaps pyenv-virtualenv has not been loaded into your shell properly. Please restart current shell and try again.
```
>you will need to add these two rows to .bashrc:
```shell
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```

**How to do it?**
* run this command in terminal:
```bash
sudo open ~/.bashrc
```

* Paste these two lines at the end of `.bashrc` file
* Restart your terminal or reload `.bashrc` file by executing this command `source ~/.bashrc`

**How to activate virtualenv using `pyenv`?**
```bash
pyenv activate <virtualenv name>
```

**How to deactivate virtualenv using `pyenv`?**
```bash
pyenv adectivate 
```

**How to run Python interpreter?**
```bash
python
```

**How to close Python interpreter?**

`Control + D`

**How to run Python file from Terminal?**
```bash
python <path to python file> (~/Desktop/hello.py)
```

> Note: All Python files should have extension `py`.

## Python

### Functions:

* print(arg) - print value of `arg` variable in terminal

### Data Types:

`str` - string. Strings should be wrapped in single quote `'`or in double quotes `"` or in three single quotes `'''` or in three double quotes `"""`

Examples of `str`:
```python
'Hello World'

"Hello World"

'''Hello 
World'''

"""Hello 
World"""
```

It is possible to concatenate (add) strings
```python
>>>print('Hello' + ' ' + 'World')
'Hello World'
```
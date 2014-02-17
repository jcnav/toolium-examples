Selenium Python
===============

Example Python project to start using Selenium WebDriver

Requirements
------------

Python 2.7.4 (http://www.python.org)

distribute 0.6.36 (https://pypi.python.org/pypi/distribute)

pip 1.3.1 (https://pypi.python.org/pypi/pip)

Installation
------------

Configure a virtual environment with the required packages:

```
virtualenv ENV
source ENV/bin/activate
pip install -r requirements_dev.txt
```

The following packages will be installed:
  * selenium (http://docs.seleniumhq.org/)

Launch tests
------------

```
python tests/register_user.py
```
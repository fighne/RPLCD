Installation
############


From PyPI
=========

You can install RPLCD directly from `PyPI
<https://pypi.python.org/pypi/RPLCD/>`_ using pip::

    $ sudo pip install RPLCD

If you want to use I²C, you also need smbus::

    $ sudo apt-get install python-smbus

If you want to use pigpio, the easiest way is to install the library via your
packet manager (select the Python version you need)::

    $ sudo apt-get install pigpio python-pigpio python3-pigpio


Manual Installation
===================

You can also install the library manually without pip. Either just copy the
scripts to your working directory and import them, or download the repository
and run ``python setup.py install`` to install it into your Python package
directory.

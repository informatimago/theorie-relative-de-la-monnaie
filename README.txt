Install
=======

Prerequisite :

* On Mac OS X : TODO
* On Ubuntu : TODO

Installation :

::

    apt-get install python-setuptools
    apt-get install python-pip
    apt-get install python-babel
    ln -s /usr/bin/pip-2.7 bin/pip
    easy_install -U distribute
    python bootstrap.py
    sudo bin/pip install -r requirements.txt
    bin/pip install https://github.com/harobed/matplotlib/archive/master.zip

Generate HTML version and PDF version
=====================================

Generate HTML version :

::

    $ make html

Generate PDF version :

::

    $ make latexpdf

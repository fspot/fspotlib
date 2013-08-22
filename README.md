Fspot Lib
=========

This is a useless module created in order to test publishing on PyPi.

Usage
-----

As this project developer, I modify the code and bump versions number. Then :

```bash
$ python setup.py register
$ python setup.py sdist upload
```

That's all, a new version of this module is available on PyPi.  
More details (french) : http://sametmax.com/creer-un-setup-py-et-mettre-sa-bibliotheque-python-en-ligne-sur-pypi/


Installation
------------

Preferably, in a virtualenv :

```bash
$ pip install fspotlib
```

Example
-------

Using as a python lib :

```bash
>>> from fspotlib import say_hi
>>> say_hi()
```

Using as a shell command :

```bash
$ fspot-say --help  # uses clize module
```

Thanks
------

Sam&Max ! (http://sametmax.com)


License
-------

WTFPL

.. _install:

Installation
============

Unix-like operating systems
---------------------------

The latest stable version is available to install using `pip <http://www.pip-installer.org/>`_:

.. code-block:: console

    # pip install livestreamer

But you can also get the development version using `Git <http://git-scm.com/>`_:

.. code-block:: console

    $ git clone git://github.com/chrippa/livestreamer.git
    $ cd livestreamer
    # python setup.py install

Windows
-------

Livestreamer is primarily developed for Unix-like operating systems where using a CLI is common. There is however an installer available for brave Windows users who don't mind using the command prompt.

The installer can be `downloaded from Github <https://github.com/chrippa/livestreamer/releases>`_. It contains a precompiled version of Livestreamer that does not require you to install any of the dependencies.

Dependencies
------------

Livestreamer currently depends on these libraries/programs to function.

To run the setup script you need:

- `Python <http://python.org/>`_ (at least version 2.6) or `PyPy <http://pypy.org/>`_
- `python-setuptools <http://pypi.python.org/pypi/setuptools>`_ or `python-distribute <http://pypi.python.org/pypi/distribute>`_


These will be installed automatically by the setup script if they are missing:

- `python-argparse <http://pypi.python.org/pypi/argparse>`_ (only needed on Python version <2.7 and <3.2)
- `python-requests <http://docs.python-requests.org/>`_ (at least version 1.0)

Optional dependencies
---------------------

For RTMP based plugins:

- `RTMPDump <http://rtmpdump.mplayerhq.hu/>`_ (Twitch/Justin.tv streams require at least version 2.4)

For decrypting encrypted HLS streams:

- `PyCrypto <https://www.dlitz.net/software/pycrypto/>`_


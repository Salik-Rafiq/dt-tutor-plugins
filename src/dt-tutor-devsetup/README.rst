dt-devsetup-plugin plugin for `Tutor <https://docs.tutor.overhang.io>`__
===================================================================================

Installation
------------

::

    pip install git+https://github.com/Dicey-Tech/dt-devsetup-plugin

Usage
-----

::

    tutor plugins enable dt-devsetup-plugin
    tutor local init -l dt_devsetup


License
-------

This software is licensed under the terms of the AGPLv3.

TODO
Config.yml
- disable forum
- use 1 uswgi worker

Run with: tutor dev exec dt_classroom ./manage.py shell_plus --notebook

Scripts
- switch outline
- generate some users
- Add Third-party authentication -> Provider Configuration (OAuth)

Switch between nightly and release builds (or any defined environment)
- set the rc file 
- 
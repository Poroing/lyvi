Lyvi
====

For more information, see http://ok100.github.io/lyvi/

About this Fork
---------------

This fork came to existence due to the lack of a fix for an issue that appeared
in the ``setup.py`` script with recent version of ``pip``. More specifically,
the ``setup.py`` script was based on a function internal to ``pip`` whose
semantics changed with an update.

Feel free to post issue and suggest pull request to this repository. I'll do
my best to take them into account.

Installation
------------

You can install the python dependencies by issuing:

.. code-block:: python

    $ sudo pip install -r pip_requirements.txt --use-mirrors

This will also be done for you when issuing the ``setup.py`` script.

There are other dependencies that need to be installed separately though:

    * ``libglyr`` (https://github.com/sahib/glyr)

For MPRIS support these dependencies are needed:

    * ``python-dbus``
    * ``python-gobject``
On OS X homebrew:

    * ``python-dbus``
    * ``pygobject``

Chances are that all these are available by your package manager.

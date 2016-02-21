Compiling
=========

Now that you've met the requirements to compile and run TrinityCore, and you've set up your build
environment, it's time to actually compile the source.


Getting the Source
------------------

To start, you need to get a copy of TrinityCore's source. It can be obtained in one of two ways,
both of which are outlined below.

Download the Source
...................

TrinityCore's source lives on GitHub.

* https://github.com/TrinityCore/TrinityCore

Periodically, new versions of TrinityCore are released by the TrinityCore maintainers. These
versions can be downloaded as ``.tgz`` files from the releases page. Make sure you download a
release marked for 3.3.5.

* https://github.com/TrinityCore/TrinityCore/releases

Cloning the Source
..................

Alternatively, if you'd prefer to have the latest version of TrinityCore, you can obtain the source
via ``git``.

To start, clone the repo using:

.. code-block:: none

   git clone git://github.com/TrinityCore/TrinityCore.git

A new directory, named ``TrinityCore``, will be created at your current working path. Switch to that
directory.

Support for version 3.3.5 is limited to the 3.3.5 branch, which can be checked out using:

.. code-block:: none

   git checkout 3.3.5

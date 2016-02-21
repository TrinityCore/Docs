Build Environment
=================

Before you can compile, you must first set up your system with an appropriate build environment.
Please follow one of the guides below.

Note that certain package names or versions may vary depending on the version of the operating
system you use.


Debian-based Linux (incl. Ubuntu)
---------------------------------

.. code-block:: none

   sudo apt-get install build-essential autoconf libtool gcc g++ make cmake git-core
   sudo apt-get install wget p7zip-full libncurses5-dev
   sudo apt-get install openssl libssl-dev mysql-server mysql-client libmysqlclient15-dev
   sudo apt-get install libmysql++-dev libreadline6-dev zlib1g-dev libbz2-dev
   sudo apt-get install libboost-dev libboost-thread-dev libboost-system-dev libboost-filesystem-dev libboost-program-options-dev

:doc:`Continue with compiling instructions... <compiling>`


RedHat-based Linux (incl. CentOS)
---------------------------------

.. code-block:: none

   yum groupinstall "Development Tools"
   yum groupinstall "Additional Development"
   yum install gcc-g++ git-core wget links zip unzip unrar cmake
   yum install mysql-server mysql-client mysql-devel
   yum install openssl

:doc:`Continue with compiling instructions... <compiling>`


Windows
-------

1. Install gitextensions
........................

`Download gitextensions <http://gitextensions.github.io/>`_

* Make sure to install all of: Git, MySYSGit, and KDiff

* When prompted, make sure to select **Run Git from the Windows Command Prompt**.

 .. thumbnail:: ../../images/git-windows-path-prompt.png

2. Install Visual Studio Community 2015
.......................................

`Download VS Community 2015 <https://www.microsoft.com/en-us/download/details.aspx?id=48146>`_

* **IMPORTANT**: The installer for VS 2015 (any edition) no longer installs the C++ compiler by
  default.

  To enable it, select **Custom** for the type of installation, and pick **Common Tools for
  Visual C++ 2015** from **Programming Languages -> Visual C++**.

  .. thumbnail:: ../../images/vs2015-cpp-install-1.png
  .. thumbnail:: ../../images/vs2015-cpp-install-2.png

3. Install Boost
................

`Download Boost <http://www.boost.org/users/download/>`_

TODO: Complete this section

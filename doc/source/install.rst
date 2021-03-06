=======
Install
=======

This section covers the basics of how to download and install 
`DXchange <https://github.com/data-exchange/dxchange>`_.

.. contents:: Contents:
   :local:


Installing from source
======================
  
Clone the `DXchange <https://github.com/data-exchange/dxchange>`_  
from `GitHub <https://github.com>`_ repository::

    git clone https://github.com/data-exchange/dxchange.git dxchange

then::

    cd dxchange
    python setup.py install


Installing from Conda/Binstar
=============================

First you must have `Conda <http://continuum.io/downloads>`_ 
installed, then open a terminal or a command prompt window and run::

    conda install -c dgursoy dxchange


Updating the installation
=========================

Data Management is an active project, so we suggest you update your installation 
frequently. To update the installation run in your terminal::

    conda update -c dgursoy dxchange

For some more information about using Conda, please refer to the 
`docs <http://conda.pydata.org/docs>`__.
    

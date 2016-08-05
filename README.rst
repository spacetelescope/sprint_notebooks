Sprint Notebooks
================

Various Jupyter notebooks from JWST DADF sprints.  This repository is
basically testing and work in progress.

This work is driven by the JWST Data Analysis Development Forum at the
`Space Telescope Science Institute <http://www.stsci.edu/>`_.

To aid in tracking down problems if someone else tries to run the
notebook, please put some comments about version numbers at the bottom
of the notebook. For example:

.. code:: python

    import sys
    import astropy
    import scipy
    print('Versions:')
    print('  python: ', sys.version_info)
    print('  astropy: ', astropy.__version__)
    print('  scipy: ', scipy.__version__)

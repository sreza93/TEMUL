.. TEMUL Toolkit documentation master file, created by
   sphinx-quickstart on Fri Jul 10 17:39:02 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. include:: define_roles.rst


Welcome to TEMUL Toolkit's documentation!
=========================================

The TEMUL Toolkit is a suit of functions and classes for analysis and visualisation of
atomic resolution images. It is mostly built upon the data structure of 
`HyperSpy <https://hyperspy.org/>`_ and `Atomap <https://atomap.org/>`_.

Interactive Examples
--------------------
The easiest way to try the TEMUL Toolkit is via Binder:
`introductory Jupyter Notebook <https://hub.gke2.mybinder.org/user/pinkshnack-temul-19r27k52/lab/tree/code_tutorials/polarisation_vectors_tutorial.ipynb>`_.
To install the TEMUL Toolkit on your own computer,
see the :ref:`install` instructions.

And there are more examples with Binder, just click the below button!

.. image:: https://mybinder.org/badge_logo.svg
   :target: https://mybinder.org/v2/gh/PinkShnack/TEMUL/0.1.7

Click the button above to start some data analysis
(it may take a few minutes to load).
The "code_tutorials" folder contains walkthroughs of some of the documentation
examples from this website.
The "publication_examples" folder will allow you to analyse data from
published scientific papers!
Just navigate to whichever of these folders you want click on the ".ipynb" files.


.. include:: about_temul_toolkit.rst


.. include:: news.rst


.. toctree::
   :maxdepth: 2
   :caption: Contents

   install
   using_temul
   workflows
   polarisation_vectors_tutorial
   structure_map_tutorial
   PTO_supercrystal_hadjimichael
   PTO_Junction_moore
   masked_fft_tutorial
   line_profile_tutorial
   dg_visualiser_tutorial
   api_doc


.. Look how easy it is to use:
    import project
    # Get your stuff done
    project.do_stuff()

.. Features
   --------
   - Be awesome


.. include:: install.rst

.. include:: using_temul.rst


Code Documentation
------------------

See the :ref:`api_doc` for examples and a full list of modules and functions.


Cite
----

To cite the latest TEMUL Toolkit version, use the following DOI:

.. image:: https://www.zenodo.org/badge/203785298.svg
   :target: https://www.zenodo.org/badge/latestdoi/203785298

For example: Eoghan O'Connell, Michael Hennessy, & Eoin Moynihan.
(2021). PinkShnack/TEMUL: (Version 0.1.3).
Zenodo. http://doi.org/10.5281/zenodo.4543963

If you wish to cite an older release of the TEMUL Toolkit, click on the above
badge to find the relevant version.


Contribute
----------

- `Issue Tracker <https://github.com/PinkShnack/TEMUL/issues>`_
- `Source Code <https://github.com/PinkShnack/TEMUL>`_

Support
-------

If you are having issues, please let us know in the issue tracker on 
`GitHub <https://github.com/PinkShnack/TEMUL/issues>`_.


License
-------

The project is licensed under the `GPL-3.0 License <https://github.com/PinkShnack/TEMUL/blob/master/LICENSE>`_.


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

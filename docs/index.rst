==============================================
SALib - Sensitivity Analysis Library in Python
==============================================

.. image:: http://readthedocs.org/projects/salib/badge/?version=latest
  :target: http://salib.readthedocs.io/en/latest/?badge=latest
  :alt: Documentation Status

.. image:: https://travis-ci.org/SALib/SALib.svg?branch=master
    :target: https://travis-ci.org/SALib/SALib

.. image:: https://coveralls.io/repos/github/SALib/SALib/badge.svg?branch=master
  :target: https://coveralls.io/github/SALib/SALib?branch=master

.. image:: https://www.quantifiedcode.com/api/v1/project/ed62e70f899e4ec8af4ea6b2212d4b30/badge.svg
  :target: https://www.quantifiedcode.com/app/project/ed62e70f899e4ec8af4ea6b2212d4b30
  :alt: Code issues

.. image:: https://zenodo.org/badge/DOI/10.5281/zenodo.160164.svg
   :target: https://doi.org/10.5281/zenodo.160164

.. image:: http://joss.theoj.org/papers/431262803744581c1d4b6a95892d3343/status.svg
  :target: http://joss.theoj.org/papers/431262803744581c1d4b6a95892d3343

Python implementations of commonly used sensitivity analysis methods, including
Sobol, Morris, and FAST methods. Useful in systems modeling to calculate the
effects of model inputs or exogenous factors on outputs of interest.

Supported Methods
-----------------
* Sobol Sensitivity Analysis
  ([`Sobol 2001 <http://www.sciencedirect.com/science/article/pii/S0378475400002706>`_], [`Saltelli 2002 <http://www.sciencedirect.com/science/article/pii/S0010465502002801>`_], [`Saltelli et al. 2010 <http://www.sciencedirect.com/science/article/pii/S0010465509003087>`_])
* Method of Morris, including groups and optimal trajectories
  ([`Morris 1991 <http://www.tandfonline.com/doi/abs/10.1080/00401706.1991.10484804>`_], [`Campolongo et al. 2007 <http://www.sciencedirect.com/science/article/pii/S1364815206002805>`_])
* Fourier Amplitude Sensitivity Test (FAST)
  ([`Cukier et al. 1973 <http://scitation.aip.org/content/aip/journal/jcp/59/8/10.1063/1.1680571>`_], [`Saltelli et al. 1999 <http://amstat.tandfonline.com/doi/abs/10.1080/00401706.1999.10485594>`_])
* Delta Moment-Independent Measure
  ([`Borgonovo 2007 <http://www.sciencedirect.com/science/article/pii/S0951832006000883>`_], [`Plischke et al. 2013 <http://www.sciencedirect.com/science/article/pii/S0377221712008995>`_])
* Derivative-based Global Sensitivity Measure (DGSM)
  ([`Sobol and Kucherenko 2009 <http://www.sciencedirect.com/science/article/pii/S0378475409000354>`_])
* Fractional Factorial Sensitivity Analysis
  ([`Saltelli et al. 2008 <http://www.wiley.com/WileyCDA/WileyTitle/productCd-0470059974.html>`_])

.. toctree::
   :maxdepth: 2

   getting-started
   basics
   api

   License <license>
   Authors <authors>
   Projects that use SALib <citations>
   Changes <changes>
   Complete Module Reference <api/modules>


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

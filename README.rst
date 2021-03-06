.. -*- mode: rst -*-

|Travis|_ |PyPi|_ |DOI|_ |PythonVersion|_

.. |Travis| image:: https://travis-ci.org/edielsonpf/wsn-toolkit.svg?branch=main
.. _Travis: https://travis-ci.org/edielsonpf/wsn-toolkit

.. |PyPi| image:: https://badge.fury.io/py/wsn-toolkit.svg
.. _PyPi: https://badge.fury.io/py/wsn-toolkit

.. |DOI| image:: https://zenodo.org/badge/319434165.svg
.. _DOI: https://zenodo.org/badge/latestdoi/319434165

.. |PythonVersion| image:: https://img.shields.io/pypi/pyversions/wsn-toolkit.svg
.. _PythonVersion: https://pypi.python.org/pypi/wsn-toolkit
   

.. |PythonMinVersion| replace:: 3.6
.. |NumPyMinVersion| replace:: 1.13.3
.. |MatplotlibMinVersion| replace:: 2.1.1
.. |PytestMinVersion| replace:: 5.0.1

**wsn-toolkit** is a Python module for simulation of Wireless Sensor Networks

Installation
------------

Dependencies
~~~~~~~~~~~~

wsn-toolkit requires:

- Python (>= |PythonMinVersion|)
- NumPy (>= |NumPyMinVersion|)

=======

Some examples require Matplotlib >= |MatplotlibMinVersion|.


User installation
~~~~~~~~~~~~~~~~~

using ``pip``::

    pip install -U wsn-toolkit

or ``conda``::

    conda install -c conda-forge wsn-toolkit


Source code
~~~~~~~~~~~

You can check the latest sources with the command::

    git clone https://github.com/edielsonpf/wsn-toolkit.git


Testing
~~~~~~~

After installation, the test suite can be exeuted from outside the source
directory (you will need to have ``pytest`` >= |PyTestMinVersion| installed)::

    pytest wsntk

Contributing
------------
From a Github account, create a feature branch from main and commit your changes with the respective tests.
Later, submit a pull request from that feature branch.

References
----------

[1]	D. A. Guimaraes, E. P. Frigieri, L. J. Sakai. *Influence of Node Mobility, Recharge, and Path Loss on the Optimized Lifetime of Wireless Rechargeable Sensor Networks*. Ad Hoc Networks, 2019.
	
[2]	Jonathan de C. Silva, Evandro L. B. Gomes, Edielson P. Frigieri. *Controle da Topologia de Redes de Sensores sem Fio para Economia de Energia Baseado no Algoritmo de Prim*. Revista da Tecnologia da Informação e Comunicação, v. 6, n. 1, pp. 9-14, 2016.	

[3]	J. C. Silva, F. Andery, D. Mazzer, E. P. Frigieri, A. Cerqueira S. Jr., L. D. P. Mendes. *Factorial Design Analysis Applied to the Performance of Transmission Power Optimization Techniques for Wireless Sensor Networks*. 	Annals of XXII Iberchip Workshop (Iberchip), 2016.
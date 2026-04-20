|Pypi Installs| |Latest Version| |Supported Python Versions|

`Mathics3 <https://mathics.org>`_ Graph Module using `NetworkX <https://networkx.org/>`_ and `Matplotlib <https://matplotlib.org>`_

Example Session
---------------

.. code-block:: mathematica

   $ mathicsscript
   Mathicscript: 10.0.0, Mathics3 10.0.0
   on CPython 3.14.3 (main, Mar 30 2026, 06:42:16) [GCC 13.3.0]

   Using:
   SymPy 1.13.3, mpmath 1.3.0, numpy 2.4.4
   cython 3.2.4, matplotlib 3.10.8,
   Asymptote version 2.95

   Copyright (C) 2011-2026 The Mathics3 Team.
   This program comes with ABSOLUTELY NO WARRANTY.
   This is free software, and you are welcome to redistribute it
   under certain conditions.
   See the documentation for the full license.

   Quit by evaluating Quit[] or by pressing CONTROL-D.


   In[1]:= LoadModule["pymathics.graph"]
   Out[1]= pymathics.graph
   In[2]:= BinomialTree[3]
   In[3]:= BinomialTree[6]
   In[4]:= CompleteKaryTree[3, VertexLabels->True]

Screenshots
-----------

|screenshot|

The above is the matplotlib graph for ``BinomialTree[3]`` in the session above.

See the `screenshot directory <https://github.com/Mathics3/Mathics3-Module-networkx/tree/master/screenshots>`_ the other graphs.

Installation
-------------

From pip:

::

   $ pip install Mathics3-Module-networkx

From git:

::

   $ make develop  # or make install

Note:
-----

Currently, this works well in `mathicsscript` but not in the Django interface, although graphs are created in a temporary directory, e.g., ``/tmp/``.


.. |screenshot| image:: https://github.com/Mathics3/Mathics3-Module-networkx/blob/master/screenshots/BinomialTree-3.png
.. |Latest Version| image:: https://badge.fury.io/py/Mathics3-Module-networkx.svg
		 :target: https://badge.fury.io/py/Mathics3-module-networkx
.. |PyPI Installs| image:: https://pepy.tech/badge/Mathics3-Module-networkx
.. |Supported Python Versions| image:: https://img.shields.io/pypi/pyversions/Mathics3-Moudle-networkx.svg
.. |Packaging status| image:: https://repology.org/badge/vertical-allrepos/Mathics3-module-networkx.svg
			    :target: https://repology.org/project/Mathics3-Module-networkx-/versions

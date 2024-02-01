Usage
=====

.. _installation:

Installation
------------

To use DriftLens, first install it using pip:

.. code-block:: console

   (.venv) $ pip install drift-lens

Compute baseline
----------------


To estimate the baseline,
you can use the ``driftlens.baseline()`` class:

.. autoclass:: lumache.get_random_ingredients

The ``pc`` parameter should be either ``"75"``, ``"100"``,
or ``"150"``. 

For example:

>>> import driftlens
>>> driftlens.Baseline()


Compute threshold
----------------

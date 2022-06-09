Usage
=====

.. _installation:

Installation
------------

To use BurnLang, first install it using git:

`Installation Page <https://github.com/Burndowntheworld/docs/edit/main/docs/source/usage.rst>`_

running *.burn
----------------

.. console:: 

e

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']


Template
========

Section
-------

Subsection
~~~~~~~~~~

You can use ``backticks`` for showing ``highlighted`` code.

`A cool website`_

.. _A cool website: https://sphinx-2-cents.readthedocs.io/en/latest

A cool bit of code::

   Some cool Code

.. code-block:: rst

   A bit of **rst** which should be *highlighted* properly.
   
.. figure::  images/image1.jpg
   :align:   center

   Just a wallpaper.
   
.. include template.rst

This is a statement.

.. warning::

   Never, ever, use this code!

.. versionadded:: 0.0.1

.. versionchanged:: 0.0.2

It's okay to use this code.


- Bullet are made like this
- Point levels must be consistent
    * Sub-bullets
        + Sub-sub-bullets
- Lists

Term
    Definition for term
Term2
    Definition for term 2

:List of Things:
    item1 - these are 'field lists' not bulleted lists
    item2
    item3

====================================

Normally you can break the line in the middle of a paragraph and it will
ignore the newline. If you want to preserve the newlines, use the ``|`` prefix
on the lines. For example:

| These lines will
| break exactly
| where we told them to.
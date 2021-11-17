Welcome to Laia's phd Documentation
===================================

This documentation is created using the library MKDOCS to be published
in **ReadTheDocs**.

How to build documentation
--------------------------

-  ``mkdocs serve`` - Start the live-reloading docs server.
-  ``mkdocs build`` - Build the documentation site. To finish the
   changes
-  ``mkdocs -h`` - Print help message and exit.
-  check ``mkdocs.yml`` - Add it in the navigation tab and add a new md
   file.

Tools to build documentation
----------------------------

To add code:
~~~~~~~~~~~~

Add a codeblock:

Just add this extra identation

::

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

Or adding the \` symbol 3 times, and the language if it is useful:

.. code:: python

    for i in range(10):
        print('hello world')

Add a code line: ``pip install xxxx``

To add links:
~~~~~~~~~~~~~

`First
link! <https://media.giphy.com/media/oyLZc4i0HlosQSfnse/giphy.gif>`__
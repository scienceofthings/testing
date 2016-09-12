Trigger Selenium installation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Trigger `Selenium <http://www.seleniumhq.org/>`_ installation so that it can be
used to run Selenium tests with the help of
`OXID testing library <https://github.com/OXID-eSales/testing_library.git>`_.

.. code:: yaml

  ---
  selenium:
    install: true

Together with Selenium, a vnc server is installed in order to connect via remote
display. Suitable clients are e.g. ``vinagre`` on Linux or the built-in vnc 
client of OS X.

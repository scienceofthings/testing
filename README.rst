First and foremost - make sure you have a working shop, meaning:

1. Shop is installed/configured (``config.inc.php`` is filled in with
   database connection details and so)
2. Shop can be accessed through url (used for shop installation).

| Several test runners are available for use once testing library is
prepared. These are available in ``bin`` or ``vendor/bin`` directory:
| ``runtests`` - run shop/module unit and integration tests.
| ``runtests-selenium`` - run shop/module selenium tests.
| ``runtests-coverage`` - run shop/module tests with code coverage.
| ``runmetrics`` - execute code metrics test for shop/module.

Additionally you can pass parameters to these scripts. ``runmetrics``
uses ``pdepend``, and all ``runtests`` uses ``phpunit``. You can add
``phpunit`` parameters to ``runtests``, ``runtests-selenium``,
``runtests-coverage``. You can add ``pdepend`` parameters to
``runmetrics``. To see which additional options can be passed to test
runner, add ``--help`` option to the command (i.e.
``./runtests --help``, ``./runmetrics --help``). This will show
available options for desired tool.

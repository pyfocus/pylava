*********
ChangeLog
*********


0.3.0 (2020-09-28)
==================

Changed
-------

- Fix compatibility with pytest 6.1.
- Drop support for Python 3.4 and add support for Python 3.8 and 3.9.


0.2.2 (2018-10-15)
==================

Fixed
-----

- Fixed typo in documentation.


Changed
-------

- Move project from https://github.com/pyfocus/pylava to
  https://github.com/pylava/pylava.


0.2.1 (2018-08-27)
==================

Fixed
-----

- Change logging level of linter errors to ERROR.


0.2.0 (2018-08-24)
==================

Changed
-------

- Allow configuration section names without ``pylava`` prefix to support
  configurations of linters that Pylava wraps around.


0.1.2 (2018-08-15)
==================

Fixed
-----

- Fix PyPI project description rendering.


0.1.1 (2018-08-15)
==================

Fixed
-----

- Set name of console script to ``pylava``.


0.1.0 (2018-08-15)
==================

Changed
-------

- Change license from BSD to MIT.


Fixed
-----

- Parse multi-options for ``pycodestyle`` correctly.
  (By Max Nordlund)
- Rename ``async`` to ``async_mode`` to make it work with Python 3.
  (By Michael Käufl)


0.0.0 (2018-08-15)
==================

This is not an actual release. This version represents the point at
which Pylava was forked from Pylama.

Pylava was forked from the ``master`` branch of Pylama version 7.4.3
(commit c38d598 dated 2017-09-17 +0300). This commit is tagged as 0.0.0.

Thus Pylava 0.0.0 is equivalent to Pylama 7.4.3.

pytest-datadir
==============


1.2.1 (2018-07-12)
------------------

- Fix ``pytest_datadir.version`` attribute to point to the correct version.


1.2.0 (2018-07-11)
------------------

- Use ``pathlib2`` on Python 2.7: this is the proper backport of Python 3's standard
  library.

1.1.0 (2018-07-10)
------------------

- If the data directory does not exist, the fixture will create an empty directory.

1.0.1 (2017-08-15)
------------------

**Fixes**

- Fixed ``shared_datadir`` contents not being copied to a temp location on each test. `#12
  <https://github.com/gabrielcnr/pytest-datadir/issues/12>`_

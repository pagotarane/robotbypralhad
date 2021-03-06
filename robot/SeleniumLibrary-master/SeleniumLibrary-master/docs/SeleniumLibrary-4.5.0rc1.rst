========================
SeleniumLibrary 4.5.0rc1
========================


.. default-role:: code


SeleniumLibrary_ is a web testing library for `Robot Framework`_ that utilizes
the Selenium_ tool internally. SeleniumLibrary 4.5.0rc1 is a new pre-release with
updated PythonLibCore to 2.1.0. The Updated PythonLibCore improves documentation
readability and offers better support IDE using Language Server Protocol with
Robot Framework test data.

All issues targeted for SeleniumLibrary v4.5.0 can be found
from the `issue tracker`_.

If you have pip_ installed, just run

::

   pip install --upgrade robotframework-seleniumlibrary

to install the latest available release or use

::

   pip install robotframework-seleniumlibrary==4.5.0rc1

to install exactly this version. Alternatively you can download the source
distribution from PyPI_ and install it manually.

SeleniumLibrary 4.5.0rc1 was released on Saturday July 11, 2020. SeleniumLibrary supports
Python 2.7 and 3.6+, Selenium 3.141.0+ and Robot Framework 3.1.2+. This is, again, last release
which contains new development for Python 2.7 and users should migrate to Python 3.

.. _Robot Framework: http://robotframework.org
.. _SeleniumLibrary: https://github.com/robotframework/SeleniumLibrary
.. _Selenium: http://seleniumhq.org
.. _pip: http://pip-installer.org
.. _PyPI: https://pypi.python.org/pypi/robotframework-seleniumlibrary
.. _issue tracker: https://github.com/robotframework/SeleniumLibrary/issues?q=milestone%3Av4.5.0


.. contents::
   :depth: 2
   :local:

Most important enhancements
===========================

Update PythonLibCore to 2.1.0 (`#1612`_, rc 1)
----------------------------------------------
PythonLibCore 2.1.0 offers cleaner library documentation and better support for
IDE using Language Server Protocol.

Acknowledgements
================

Overwriding the EMBED in the screenshot keywords creates EMBED folder (`#1614`_, rc 1)
--------------------------------------------------------------------------------------
Many thanks for Ossi R. for fixing bug when screen shot keywords overwrite the
Set Screen Shot Directory EMBED argument. This in case extra EMBED directory was
created.

Fix typo in extending documentation (`#1601`_, rc 1)
----------------------------------------------------
Many thanks for humbienri for fixing typo in the extending.rst documentation.


Full list of fixes and enhancements
===================================

.. list-table::
    :header-rows: 1

    * - ID
      - Type
      - Priority
      - Summary
      - Added
    * - `#1614`_
      - bug
      - high
      - Overwriding the EMBED in the screenshot keywords creates EMBED folder
      - rc??1
    * - `#1612`_
      - enhancement
      - high
      - Update PythonLibCore to 2.1.0
      - rc??1
    * - `#1601`_
      - bug
      - medium
      - Fix typo in extending documentation
      - rc??1
    * - `#1604`_
      - bug
      - medium
      - Fix doc bugs in page should not * keywords. 
      - rc??1

Altogether 4 issues. View on the `issue tracker <https://github.com/robotframework/SeleniumLibrary/issues?q=milestone%3Av4.5.0>`__.

.. _#1614: https://github.com/robotframework/SeleniumLibrary/issues/1614
.. _#1612: https://github.com/robotframework/SeleniumLibrary/issues/1612
.. _#1601: https://github.com/robotframework/SeleniumLibrary/issues/1601
.. _#1604: https://github.com/robotframework/SeleniumLibrary/issues/1604

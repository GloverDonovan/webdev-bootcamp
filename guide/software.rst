Software and Tools
==================

The software you'll need to download and install on your computer in order to
contribute varies between projects; please refer to the documentation for the
project you want to contribute to for details.

Below is a list of some of the software you'll most likely need regardless of
the project you work on.

Operating Systems: Windows, Linux, or macOS?
--------------------------------------------

Most of our sites are developed on macOS or Linux, and deployed to servers
running Linux. If you are a Windows user, you may want to use a program like
`VirtualBox`_ to create a virtual machine running a Linux-based operating
system. The rest of this guide assumes you are using macOS or any Linux-based
operating system.

If you are running macOS, most of the software mentioned here can be
installed using the `Homebrew`_ package manager.

.. _VirtualBox: https://www.virtualbox.org/
.. _Homebrew: https://brew.sh/

Git
---

Git_ is a distributed version control system. It tracks the history of changes
we make to our code, which allows us to see how the code has changed over time.
Git also makes it very easy for multiple people to work on the same code at the
same time and merge their changes together at the end.

.. seealso::

   `help.github.com <https://help.github.com/>`_
      A great guide to getting start with Git and GitHub, which hosts most of
      our Git repositories.

   `GitHub Desktop <https://desktop.github.com/>`_
      A graphical user interface for interacting with GitHub repositories.
      GitHub Desktop works on Windows and macOS and is useful if you're not
      used to working with Git in the terminal yet.

.. _Git: https://git-scm.com/

Python
------

Python_ is a programming language that many of our websites use for their
back-end code. Most of our Python-based sites are implemented using Django_,
a Python framework for making websites.

Most of our Python-based sites are developed to run under Python 2, and most
of our servers run the sites on Python 2.

.. seealso::

   `The Hitchhiker's Guide to Python <http://docs.python-guide.org/>`_
      A useful guide for beginner and expert Python developers. If you need to
      install Python on your computer, this guide will help!

.. _Python: https://www.python.org/
.. _Django: https://www.djangoproject.com/

Node.js
-------

`Node.js`_ is a JavaScript-based runtime for building network applications,
including websites. An increasing amount of Mozilla projects are being written
as Node applications.

.. seealso::

   `nodejs.org Downloads <https://nodejs.org/download/>`_
      The official Node.js download page, which includes installers for Windows
      and macOS. If you're using a Linux distribution, it's best to install
      Node.js with your package manager.

.. _Node.js: https://nodejs.org/

Miscellaneous
-------------------

The following is a list of software you probably need that don't merit a
heading:

- `GNU gettext`_: Used for localization support on many websites. Can usually
  be installed via your package manager under the name ``gettext``.

.. _GNU gettext: https://www.gnu.org/software/gettext/

*Create and install Info docs from GitHub RST documentation*

Usage
-----
Change the script so that $d points to your info directory. Then,
execute the script with the URL of the GitHub repository's
documentation directory (the one that contains the Sphinx conf.py
file)::
  
  $ ./github2info "https://github.com/path-to-repository/tree/master/path-to-doc-directory"
  
Requirements
------------
* An Info reader
* `Texinfo`_
* `Sphinx`_
* `Subversion`_

Example usage
-------------
Creating and installing the Sphinx documentation::

  $ ./github2info "https://github.com/sphinx-doc/sphinx/tree/master/doc"

Issues
------

Some projects (e.g. Python itself) require you to install additional
tools besides Sphinx to build the documentation. In that case, this
script should work once you have installed the proper tools.
  
.. _Texinfo: https://www.gnu.org/software/texinfo/
.. _Sphinx: http://www.sphinx-doc.org/en/master/
.. _Subversion: https://subversion.apache.org/

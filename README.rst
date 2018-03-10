*Create and install Info docs from GitHub RST documentation*

Usage
-----
Change the script so that $d points to your info directory. Then,
execute the script with the URL of the GitHub repository's
documentation directory::
  
  $ ./github2info "https://github.com/path-to-repository/tree/master/path-to-doc-directory"
  
Requirements
------------
* An Info reader
* `Texinfo`_
* `Sphinx`_
* `Subversion`_

Example usage
=============
Creating and installing the Sphinx documentation::

  $ ./github2info "https://github.com/sphinx-doc/sphinx/tree/master/doc"

.. _Texinfo: https://www.gnu.org/software/texinfo/
.. _Sphinx: http://www.sphinx-doc.org/en/master/
.. _Subversion: https://subversion.apache.org/

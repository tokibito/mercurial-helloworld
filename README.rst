==============================
Helloworld mercurial extension
==============================

1. Install Mercurial and extension

::

   $ virtualenv venv --python=python2.7
   $ source venv/bin/activate
   (venv)$ pip install mercurial-extension-helloworld

2. Write ~/.hgrc

::

   [extensions]
   helloworld=

3. Run ``hg hello`` command

::

   (venv)$ hg hello
   Hello world!

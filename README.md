phtum.buildout
==============

Installation Short Version
--------------------------

- Check out from github 
- run the ./init script

Installation Long Version
-------------------------

- Check out from github 
- create a virtualenv
  virtualenv --no-site-packages --clear --python python2.7 .
- probably upgrade setuptools
  bin/pip install setuptools==1.3.1
- run bootstrap
  bin/python bootstrap.py
- run buildout
  bin/buildout


Subsequent config updates
-------------------------

Just run bin/buildout whenever you have updated your buildout.cfg

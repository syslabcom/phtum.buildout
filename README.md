phtum.buildout
==============

- Check out from github 
- create a virtualenv
  virtualenv --no-site-packages --clear --python python2.7 .
- probably upgrade setuptools
  pip install setuptools==1.3.1
- run bootstrap
  bin/python bootstrap.py
- run buildout
  bin/buildout

# NodeFabric documentation

http://nodefabric.readthedocs.org/en/latest/

## Local copy

git clone https://github.com/opennode/nodefabric-docs.git

## Setting up local build environment for docs 

Installing python-sphinx on MacOSX:
```bash
brew install python
pip install --upgrade pip setuptools
easy_install -U sphinx
pip install sphinx_bootstrap_theme
pip install sphinx_rtd_theme
pip install sphinx-autobuild
```

## Creating and building

Bootstrapping new local sphinx doc:
```bash
mkdir docs
cd docs
sphinx-quickstart
vim index.rst
```

Building documentation locally:
```bash
cd docs
make html
# open from browser
file://../nodefabric-docs/docs/_build/html/index.html
```

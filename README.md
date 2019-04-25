Tenorpy is an updated Python wrapper for the Tenor API.

Installation
===============
Clone Rpository

``python setup.py install``

or install with pip

``pip install -i https://test.pypi.org/simple/ tenorpy``

Usage
=====
**GIF Endpoints**

To use:

````python
import tenorpy
t = tenorpy.Tenor()
print(t.random("GIFTAG"))
# Will return a random GIF with the tag "GIFTAG"
````

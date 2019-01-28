Tutorials
---

I like to use [virtualenv](https://pypi.org/project/virtualenv/) to make sure I'm running a clean environment. 

To create a Python3 virtual environment:

``
virtualenv --no-site-packages -p python3 p3env
``

then activate it:

``
source p3env/bin/activate
``

You can then install all of the libraries for these tutorials using:

``
pip3 install -r requirements.txt
``

# deeplearning-udacity
There were challenges installing the matplotlib, had to follow these steps before installing matplotlib:

- sudo pip install scipy
- sudo pip install sklearn
- sudo apt-get install libpng-dev
-  sudo apt-get install libfreetype6-dev
- sudo pip install matplotlib

While running the example from Assignment 1, following packages were not getting resolved in STS:
from six.moves.urllib.request import urlretrieve
from six.moves import cPickle

To fix the import issue, had to go to<b>
     Project --> PyDev - Interpreter/Grammar-->Under Interpreter click... "Click here to configure an interpreter not listed" --> Forced Builtins --> Click "New" --> Type "six" and click OK.</b>

While executing the program, there was an error:
<br>
    
    ImportError: Could not import the Python Imaging Library (PIL) required to load image files. Please refer to http://pypi.python.org/pypi/PIL/ for installation instructions.
</br>
To resolve this error, pillow had to be installed:

- sudo pip install pillow

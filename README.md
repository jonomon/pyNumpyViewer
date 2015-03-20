# pyNumpyViewer
When you want to print long numpy arrays, it appears as:

    np.ones([1000, 1])
    array([ 1.,  1.,  1., ...,  1.,  1.,  1.])

pyNumpyViewer opens the numpy array in the webbrowser and allows you to examine each element.

## Usage

pyNumpyViewer is used by simply calling:

    pyNumpyViewer(numpy_array, sigFig=3)
    
## Installation

Requirements: numpy

Install by:

    python setup.py install

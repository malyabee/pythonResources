How to install wheel files (.whl) python file

Step 1. Download python package .whl extention 

Step 2. python -m pip install  <package name>

(or)
 
pip install --no-index  --find-links=<directory to whl file location> <package_name>

 



https://www.youtube.com/watch?v=tDwOhlJAV2s


## How to build .whl python file.
step1. install wheel package

    $ pip install wheel
    
## How to package source distination pacage  package

    $ python setup.py sdist    

## How to package this as wheel distribution 
     python setup.py bdist_wheel --universal  --dist-dir wdist



## References 
Python Packaging User Guide
https://python-packaging-user-guide.readthedocs.io/


# README.md

## What is required to run astrodatalab notebooks on DESI




### Installation of DESI packages


#### desiutil
- https://github.com/desihub/desiutil :

   git clone git@github.com:desihub/desiutil.git
   cd desiutil
   pip install .

#### desitarget
- https://github.com/desihub/desitarget :

    git clone git@github.com:desihub/desitarget.git  
    python setup.py install 

### Noirlab astroddatalab

#### sparclclient

    pip install sparclclient


#### datalab

- https://github.com/astro-datalab/datalab

    git clone git@github.com:astro-datalab/datalab.git
    cd datalab/

    python -m pip install --upgrade pip setuptools
    python -m pip install build
    python -m build

    **Successfully built** **astro_datalab-2.24.0.tar.gz** **and** **astro_datalab-2.24.0-py3-none-any.whl**

    pip install dist/astro_datalab-2.24.0-py3-none-any.whl 



# Installation

The package can be installed from [PyPi](https://pypi.org/project/nbjoint/) with

```bash
pip install nbjoint
```

It can also be downloaded directly from github.com/rmsrosa/nbjoint and installed, from the downloaded package directory, with

```bash
pip install .
```

If you do not wish to install the package, you can simply download it and import it as a local module as follows:

- If the subdirectory `nbjoint` of the project is in the same folder as the script that will import it, simply do

  ```python
  import nbjoint as nbj
  ```

- If the subdirectory `nbjoint` is in a different location, use

  ```python
  import os
  import sys

  sys.path.insert(0, os.path.abspath(os.path.join(os.getcwd(), 'path', 'from', 'script', 'to', 'module')))

  import nbjoint as nbj
  ```

In case of downloading the package and using it or installing it locally, you just need the file `nbjoint.py` in the root directory`.

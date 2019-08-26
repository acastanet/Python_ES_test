# Python environment with requirements.txt

[! [Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/acastanet/Python_ES/master)



A Binder-compatible repo with a `requirements.txt` file.

Access this Binder at the following URL 

https://mybinder.org/v2/gh/acastanet/Python_ES/master

.. image :: https://mybinder.org/badge_logo.svg
 : cible: https://mybinder.org/v2/gh/acastanet/Python_ES/master

## Notes
The `requirements.txt` file should list all Python libraries that your notebooks
depend on, and they will be installed using:

```
pip install -r requirements.txt
```

The base Binder image contains no extra dependencies, so be as
explicit as possible in defining the packages that you need. This includes
specifying explict versions wherever possible.

In this example we include the library `seaborn` which will be installed in
the environment, and our notebook uses it to plot a figure.

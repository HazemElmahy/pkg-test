# Creating the package
* create empty  ```__init__.py```

* create 
  1. ```setup.cfg``` for Static metadata: guaranteed to be the same every time. This is simpler, easier to read, and avoids many common errors, like encoding errors.
  2. ```setup.py``` for Dynamic metadata: possibly non-deterministic. Any items that are dynamic or determined at install-time, as well as extension modules or extensions to setuptools, need to go into setup.py.

* create ```pyproject.toml``` tells build tools (like pip and build) what is required to build your project. 


# Installing the package
```!pip install git+https://github.com/HazemElmahy/pkg-test.git```

# Importing the package
``` from pkg_test.pkg import sayWord```

**from Package_name.Module_name import Function**

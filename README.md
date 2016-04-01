# python-boilerplate

A collection of very simple [boilerplates](#boilerplates) for Python projects. See [features](#features), [structure](#structure) and [glossary](#glossary) to better understand them.

## Boilerplates

* [module](https://github.com/fernandojunior/python-boilerplate-module) - Boilerplate to create a module based project.
* [package](https://github.com/fernandojunior/python-boilerplate-package) - Boilerplate to create a package based project.
* [script](https://github.com/fernandojunior/python-boilerplate-script) - Boilerplate to create a script based project.

## Features
*Common preconfigured tools to facilitate the project development.*

* [coverage.py](https://coverage.readthedocs.org/) - Code coverage measurement.
* [Flake8](https://flake8.readthedocs.org/) - The modular source code checker: pep8, pyflakes and co.
* [pytest](http://pytest.org/) - A mature full-featured Python testing tool.
* [setuptools](https://pythonhosted.org/setuptools/setuptools.html) - Easily download, build, install, upgrade, and uninstall distribution packages.
* [tox](https://tox.readthedocs.org/) - Auto builds and tests distributions in multiple Python versions using virtualenvs.

## Structure
*Basic structure of the boilerplates in [tree](http://stackoverflow.com/questions/3455625/linux-command-to-print-directory-structure-in-the-form-of-a-tree) format.*

```sh
├── <CORE_CODE>  # Python package or module with the core code of the project
├── CONTRIBUTING.md  # Details about how project owner would like to receive contributions
├── LICENSE  # Informs users and contributors what they can and can't do with the project
├── Makefile  # Automates useful tasks to use with make, a build automation tool
├── MANIFEST.in  # Adds extra resources in distributions packages
├── README.md  # Details how to build, install, use and contribute to the project
├── requirements*  # Contains the dependencies of the project to be installed using pip
├── setup.cfg  # Configures some settings of the tools used in the project
├── setup.py  # Contains information needed to build distributions with setuptools
├── tests*  # Provides some automated tests to run with pytest
└── tox.ini  # Defines test environments to run with tox
```

## Glossary
*Terms to understand the capabilities offered by the boilerplates.*

* `build` - Refers to preparing a project in a `distribution package` that users can install and use easily.
* `dependency` - A `distribution package` that is required to `build`, install and use a `project`.
* `distribution package` - A archive file with `packages`, `modules` or other resources used to distribute a `release`.
* `module` - A .py file that serves as a unit of Python source code which can expose variables, functions and classes.
* `package` - A directory containing an \_\_init\_\_.py file and which can contain `modules` or recursively, other `packages`.
* `pip` - The preferred package manager system for installing `distribution packages`.
* `project` - A library, framework, script, plugin, application, or other resources or some combination thereof.
* `release` - A snapshot of a `project` at a particular point in time, denoted by a version identifier.
* `virtualenv` - A tool to isolate a environment of a `project` and its `dependencies` from a Python installation.

Other nice glossaries at [Python Documentation](https://docs.python.org/3/glossary.html), [Python Packaging User Guide](https://python-packaging-user-guide.readthedocs.org/en/latest/glossary/) and [Setuptools' Documentation](http://pythonhosted.org/setuptools/pkg_resources.html).

## Contributing

See [CONTRIBUTING](/CONTRIBUTING.md).

## License

[![CC0](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

The MIT License.

-

Copyright (c) 2016 [Fernando Felix do Nascimento Junior](https://github.com/fernandojunior/).

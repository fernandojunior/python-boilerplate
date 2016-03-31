# python-boilerplate

This repository contains a collection of very simple boilerplates for Python projects. All them have common [features](#features) and basic [structure](#structure). See also a tiny [glossary](#glossary) to better understand.

* [module](https://github.com/fernandojunior/python-boilerplate-module) - Boilerplate to create a Python module based project.
* [package](https://github.com/fernandojunior/python-boilerplate-package) - Boilerplate to create a Python package based project.
* [script](https://github.com/fernandojunior/python-boilerplate-script) - Boilerplate to create a Python script based project.

## Features
*Common preconfigured tools to facilitate the project development.*

* [coverage.py](https://coverage.readthedocs.org/) - Code coverage measurement.
* [Flake8](https://flake8.readthedocs.org/) - The modular source code checker: pep8, pyflakes and co.
* [pytest](http://pytest.org/) - A mature full-featured Python testing tool.
* [setuptools](https://pythonhosted.org/setuptools/setuptools.html) - Easily download, build, install, upgrade, and uninstall distribution packages.
* [tox](https://tox.readthedocs.org/) - Auto builds and tests distributions in multiple Python versions using virtualenvs.

## Structure
*Structure of the project in [tree](http://stackoverflow.com/questions/3455625/linux-command-to-print-directory-structure-in-the-form-of-a-tree) format.*

```sh
├── <CORE_CODE>
├── CONTRIBUTING.md
├── LICENSE
├── Makefile
├── MANIFEST.in
├── README.md
├── requirements
│   ├── dev.txt
│   └── prod.txt
├── requirements.txt
├── setup.cfg
├── setup.py
├── tests*
└── tox.ini
```

Purpose of each file:

* \<CORE_CODE\> - A Python package or module with the core code of the project.
* CONTRIBUTING.md - Details about how project owner would like to receive contributions [reference](https://guides.github.com/activities/contributing-to-open-source/).
* LICENSE - Informs users and contributors what they can and can't do with the project [reference](https://guides.github.com/activities/contributing-to-open-source/).
* Makefile - Automates useful commands to use with make, a build automation tool [reference](https://en.wikipedia.org/wiki/Makefile).
* MANIFEST.in - Adds extra resources in distributions as only modules and packages are included by default [reference](https://pythonhosted.org/setuptools/setuptools.html).
* README.md - Details for the project on how to build, install, use and contribute to it [reference](https://guides.github.com/activities/contributing-to-open-source/).
* requirements* - Contains the dependencies of the project to be installed using pip [reference](https://pip.readthedocs.org/en/stable/user_guide/#requirements-files).
* setup.cfg - Configures some settings of the tools used in the project [reference](https://docs.python.org/3/distutils/configfile.html).
* setup.py - Contains information needed to build, release and install distributions [reference](https://pythonhosted.org/setuptools/setuptools.html).
* tests* - Provides some automated tests to run with pytest [reference](http://pytest.org/).
* tox.ini - Defines test environments to run with tox [reference](https://tox.readthedocs.org/en/latest/).

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

[![Sourcecode on GitHub](https://img.shields.io/badge/BuildTheDocs-sphinx.graphviz-323131.svg?logo=github&longCache=true)](https://github.com/buildthedocs/sphinx.graphviz)
<!--[![License](https://img.shields.io/badge/Apache%20License,%202.0-bd0000.svg?longCache=true&label=code%20license&logo=Apache&logoColor=D22128)](LICENSE.md)-->
[![GitHub tag (latest SemVer incl. pre-release)](https://img.shields.io/github/v/tag/buildthedocs/sphinx.graphviz?logo=GitHub&include_prereleases)](https://github.com/buildthedocs/sphinx.graphviz/tags)
[![GitHub release (latest SemVer incl. including pre-releases)](https://img.shields.io/github/v/release/buildthedocs/sphinx.graphviz?logo=GitHub&include_prereleases)](https://github.com/buildthedocs/sphinx.graphviz/releases/latest)
[![GitHub release date](https://img.shields.io/github/release-date/buildthedocs/sphinx.graphviz?logo=GitHub&)](https://github.com/buildthedocs/sphinx.graphviz/releases)
[![Libraries.io status for latest release](https://img.shields.io/librariesio/release/pypi/btd.sphinx.graphviz)](https://libraries.io/github/buildthedocs/sphinx.graphviz)
[![Requires.io](https://img.shields.io/requires/github/buildthedocs/sphinx.graphviz)](https://requires.io/github/buildthedocs/sphinx.graphviz/requirements/?branch=master)  
<!--[![Travis](https://img.shields.io/travis/com/buildthedocs/sphinx.graphviz?logo=Travis)](https://travis-ci.com/buildthedocs/sphinx.graphviz)-->
[![PyPI](https://img.shields.io/pypi/v/btd.sphinx.graphviz?logo=PyPI)](https://pypi.org/project/btd.sphinx.graphviz/)
![PyPI - Status](https://img.shields.io/pypi/status/btd.sphinx.graphviz?logo=PyPI)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/btd.sphinx.graphviz?logo=PyPI)
[![Dependent repos (via libraries.io)](https://img.shields.io/librariesio/dependent-repos/pypi/btd.sphinx.graphviz)](https://github.com/buildthedocs/sphinx.graphviz/network/dependents)  
<!-- [![Read the Docs](https://img.shields.io/readthedocs/btd-sphinx-graphviz)](https://btd-sphinx-graphviz.readthedocs.io/en/latest/)-->

# btd.sphinx.graphviz

This is a patched version of [`sphinx.ext.graphviz`](https://github.com/sphinx-doc/sphinx).

> **Note:**  
> Patched versions of internal packages from Sphinx are released as M.M.P.postN
> versions. So `2.3.1.post1` is the patched module version derived from Sphinx
> `2.3.1`.

--------------------

## Added features and changes

* `4.3.1.post1`
  * Updates sources to match Sphinx 4.3.1
* `2.3.1.post1`
  * Updated directive options according to documentation (see: [sphinx-doc/sphinx#6991](https://github.com/sphinx-doc/sphinx/issues/6991#issuecomment-573446371))

## Cross-References

* [`sphinx.ext.inheritance_diagram`](https://github.com/sphinx-doc/sphinx)  
  If inheritance diagrams are enabled as an extension in Sphinx, these will
  reference `graphviz` and cause an `ImportError`. Please also install the
  patched variation [`btd.sphinx.inheritance_diagram`](https://github.com/buildthedocs/sphinx.inheritance_diagram),
  which patches internal cross-references.

--------------------

## Install using `pip`

```
$ pip install btd.sphinx.graphviz
```

----------------------

SPDX-License-Identifier: BSD-2-Clause

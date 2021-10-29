# mwdblib

API bindings for [mwdb.cert.pl](https://mwdb.cert.pl) service or your own instance of [MWDB](https://github.com/CERT-Polska/mwdb-core), supporting both Python 2.x/3.x versions.
Use it if you want to automate data uploading/fetching from MWDB or have some ipython-based CLI.

## Usage and installation

```
$ pip install mwdblib

or with CLI

$ pip install mwdblib[cli]
$ mwdb version
```

Complete docs can be found here: https://mwdblib.readthedocs.io/en/latest/

## Development install

Want to support the development or review a pull request? Install from source:

```
git clone https://github.com/CERT-Polska/mwdblib.git
cd mwdblib
git checkout your_branch  # optional, if not master
pip install .[cli]  # install package along with the cli module
```

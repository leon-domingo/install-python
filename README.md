# Bash script to download and install a specific version of Python

The usage is very simple

```shell
./install-python <version> <path>
```

Both _version_ and _path_ are required.

For example,

```shell
./install-python 3.6.8 /home/username/python
```

It will download and install **Python 3.6.8** into the folder _/home/username/python/python3.6.8_. The _path_ can be indicated with or without a trailing slash. So these two are equivalent:

```shell
./install-python 3.6.8 /some/path/to/install/python/
```

```shell
./install-python 3.6.8 /some/path/to/install/python
```

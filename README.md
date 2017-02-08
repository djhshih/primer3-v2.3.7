# primer3

This is a fork of primer3 (version 2.3.7) with addition contents: an installation script and a wrapper script for command line execution.

## Installation

By default, the programs the configuration files are installed to a local `build` directory.

```{bash}
make install
```

To install to `/usr/local`, do:

```{bash}
make install DESTDIR=/usr/local
```

## Usage

```{bash}
primer3
```

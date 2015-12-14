Build from source
=================

For Ubuntu/Debian

## Install prerequisites

```
sudo apt-get install automake autoconf make
```

## Create user / group 'eprints'

```
sudo useradd eprints
```

## Run autotool chain

```
aclocal
autoconf
automake --add-missing
./configure
make
```

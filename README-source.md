Build from source
=================

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

# LibGATT
This is simply the [BlueZ 5.7](http://www.bluez.org/) GATT/LE code extracted into a library (since they didn't see fit to include it in their bluetooth library).

## How to build

Simply execute the following commands:

```
$ ./bootstrap
$ ./configure
$ make -j`nproc`

```

To install:

```
# make install
```

To install to a different dir (e.g. locally instead of system-wide), use the `--prefix` parameter to the `configure` script:

```
$ ./configure --prefix=</local/install/path>
$ make -j`nproc`
# make install
```

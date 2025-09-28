# Seengreat POE fan HAT examples

This is from this [wiki link](https://seengreat.com/wiki/133/poe-fan-hat-c), where on the end of the document it provides the C/Python examples for the POE hat.

## How to

```
git clone --recurse-submodules https://github.com/Filipe-Souza/seengreat-poe-fan-hat-c
```

Already cloned?

```
git submodule update --init --recursive
```

Enter the *lg* directory and build the library:

```
cd lg
make
sudo make install
```

Enable the I2C interface on your Raspberry Pi and reboot.

Test the examples.

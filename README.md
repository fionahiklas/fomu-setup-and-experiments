# FOMU Setup and Experiments

## Overview 

FOMU FPGA Board setup and experiments

From the [Tomu family of boards](https://tomu.im)

Main [Fomu page](https://tomu.im/fomu.html)

The [Fomu toolchain repo](https://github.com/im-tomu/fomu-toolchain)


## Notes

### Reading through Workshop

The [Fomu Workshop](https://workshop.fomu.im/en/latest/) seems like it provides
a wealth of information and step-by-step guide.

The first command mentioned is this one

```
dfu-util -l
```

There is a [man page for this](https://manpages.ubuntu.com/manpages/xenial/en/man1/dfu-util.1.html) it does device firmware updates over USB.

You appear to be able to install on Mac (tested on M1 Mac) using 

```
brew install dfu-util
```

Getting the workshop files with this command

```
git clone --recurse-submodules https://github.com/im-tomu/fomu-workshop.git
```


## References

### Unbricking

* [Group conversation about bricked fomu](https://groups.google.com/g/tomu-discuss/c/1s6sDbHXgnc)
* [Production version hardware](https://github.com/im-tomu/fomu-hardware/tree/master/archive/pvt)
* [Test points image](https://github.com/im-tomu/fomu-hardware/blob/master/archive/pvt/images/fomu_pvt_test_points.jpg)
* [Fomu flash tool](https://github.com/im-tomu/fomu-flash)
* [Factory test](https://github.com/im-tomu/fomu-factory-test)
* [Bricking issue fixed in dfu-util](https://github.com/im-tomu/foboot/issues/330)
* [foboot Bootloader softcore](https://github.com/im-tomu/foboot)




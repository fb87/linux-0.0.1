# README

## To able to compile and run on f36, some tools need to be installed:

```bash
sudo dnf install dev86                                      # as86, ar86, etc.,
sudo dnf install make gcc glibc-devel.i686 qemu-system-i386 # used to produce 32bits kernel
```

## To able to compile and run on Ubuntu 20.04, some tools need to be installed:

```bash
sudo apt install bin86                                                 # as86, ar86, etc.,
sudo dnf install binutils build-esential gcc-multilib qemu-system-i386 # used to produce 32bits kernel
```

## Build and run

* Compile with `make -j$(nproc)`
* Run with `unzip hd_oldlinux.img.zip && make run`
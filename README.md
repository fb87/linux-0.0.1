# README

To able to compile and run on f36, some tools need to be installed:

```bash
sudo dnf install dev86                          # as86, ar86, etc.,
sudo dnf install make gcc glibc-devel.i686 qemu # used to produce 32bits kernel
```

* Compile with `make -j$(nproc)`
* Run with `unzip hd_oldlinux.img.zip && make run`


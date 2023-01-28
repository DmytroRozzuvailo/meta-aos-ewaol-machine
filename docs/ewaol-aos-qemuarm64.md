# EWAOL on generic arm64 Documentation


## Status

The baremetal image compiles, It has not yet been tested on real hardware.

## Building

```bash
./build.sh ewaol-aos-qemuarm64 baremetal
```

## Installing

Assuming your SD card is at ```/dev/mmcblk0```.

```bash
#TODO: Not done this yet
```

## Serial Console

```bash
#TODO: Not done this yet
```

## Run

```
./layers/meta-aos-ewaol/meta-aos-ewaol/scripts/qemu_start.sh ${PATH_TO_WORKDIR}/meta-aos-ewaol-machine/build/ewaol-aos-qemuarm64/tmp_baremetal/deploy/images/ewaol-aos-qemuarm64/Image ${PATH_TO_WORKDIR}/meta-aos-ewaol-machine/build/ewaol-aos-qemuarm64/tmp_baremetal/deploy/images/ewaol-aos-qemuarm64/ewaol-aos-vm-image-ewaol-aos-qemuarm64.ext4
```

## Known issues

- baremetal image not tested
- virtualization image not tested
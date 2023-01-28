# meta-aos-ewaol-machine
EWAOL Aos integration into VM (based on generic-arm64)

Extra machines for [EWAOL-AOS](https://github.com/DmytroRozzuvailo/meta-aos-ewaol)

## Build

Install the kas tool, ensuring you have a version 3.0.2 or greater, by following the instructions
[here](https://kas.readthedocs.io/en/latest/userguide.html).

To build ewaol-aos, use the helper script ```build.sh``` which gives a consistent way of building for the target platforms.

```bash
# Building for the ewaol-aos-qemuarm64 target
./build.sh ewaol-aos-qemuarm64 baremetal
```

## Run

```
./layers/meta-aos-ewaol/meta-aos-ewaol/scripts/qemu_start.sh ${PATH_TO_WORKDIR}/meta-aos-ewaol-machine/build/ewaol-aos-qemuarm64/tmp_baremetal/deploy/images/ewaol-aos-qemuarm64/Image ${PATH_TO_WORKDIR}/meta-aos-ewaol-machine/build/ewaol-aos-qemuarm64/tmp_baremetal/deploy/images/ewaol-aos-qemuarm64/ewaol-aos-vm-image-ewaol-aos-qemuarm64.ext4
```

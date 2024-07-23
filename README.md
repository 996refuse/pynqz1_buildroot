# pynqz1_buildroot

### How to use

```sh
$ git clone https://gitlab.com/buildroot.org/buildroot
$ cd buildroot
$ git checkout -b 2024.05-rc2
$ make BR2_EXTERNAL=../pynqz1_buildroot zynq_pynqz1_defconfig
$ make all
```


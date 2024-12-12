# Bottlerocket Kernel Kit
This is the kernel kit for [Bottlerocket](https://github.com/bottlerocket-os/bottlerocket).
It includes Linux kernels and dependencies for downstream package and variant builds.

## Contents
The kernel kit includes:
* multiple versions of the Linux kernel
* bootloaders
* firmware

### Availability
The [Bottlerocket kernel kit](https://gallery.ecr.aws/bottlerocket/bottlerocket-kernel-kit) is available through Amazon ECR Public.

### Development
The kernel kit can be built on either an **x86_64** or an **aarch64** host. To do this you can use the following commands.
```shell
make
```
OR
```shell
make ARCH=<aarch64, x86_64>
```
See the [BUILDING](BUILDING.md) guide for more details.

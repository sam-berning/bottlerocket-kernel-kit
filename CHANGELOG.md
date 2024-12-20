# 1.0.1 (2024-12-20)

## OS Changes
* Update to kernel 5.10.230 and 5.15.173 ([#10])

## Build Changes
* Add GPG verification where possible ([#5])

[#5]: https://github.com/bottlerocket-os/bottlerocket-kernel-kit/pull/5
[#10]: https://github.com/bottlerocket-os/bottlerocket-kernel-kit/pull/10

# 1.0.0 (2024-12-11)

## Build Changes
* Create the new kernel kit from the following core-kit packages: ([#1])
  * grub
  * kernel-5.10
  * kernel-5.15
  * kernel-6.1
  * kmod-5.10-nvidia
  * kmod-5.15-nvidia
  * kmod-6.1-nvidia
  * libkcapi
  * linux-firmware
  * microcode
  * shim
* Update bottlerocket-sdk to v0.50.0

[#1]: https://github.com/bottlerocket-os/bottlerocket-kernel-kit/pull/1

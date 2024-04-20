# crosstool-ng-actions

Use Github Actions to build toolchain using [crosstool-ng](https://crosstool-ng.github.io/) and create a release.

Currently, following tool chains are produced:

- Target: Alpine ARM64 musl (aarch64-alpine-linux-musl-gcc-11_3_0.tar.gz)
- Target: Alpine AMD64 musl (x86_64-alpine-linux-musl-gcc-11_3_0.tar.gz)
- Target: AmazonLinux 2023 ARM64 (aarch64-aws2023-linux-gnu-glibc-2.34-gcc-11_3_0.tar.gz)
- Target: RHEL 8 ARM64 (aarch64-rhel8-linux-gnu-glibc-2.28-gcc-8_5_0.tar.gz)
- Target: RHEL 9 ARM64 (aarch64-rhel9-linux-gnu-glibc-2.34-gcc-11_3_0.tar.gz)

All toolchain's host platform is modern Linux AMD64 OS, typically Ubuntu 22.04 is tested.

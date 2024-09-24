 # crosstool-ng-actions

Use Github Actions to build toolchain using [crosstool-ng](https://crosstool-ng.github.io/) and create a release.

Currently, following tool chains are produced:

- Target: AmazonLinux 2 x86_64 (x86_64-aws2-linux-gnu-glibc-2.26-gcc-7.tar.gz, x86_64-aws2-linux-gnu-glibc-2.26-gcc-8.tar.gz)
- Target: AmazonLinux 2 aarch64 (aarch64-aws2-linux-gnu-glibc-2.26-gcc-7.tar.gz, aarch64-aws2-linux-gnu-glibc-2.26-gcc-8.tar.gz)
- Target: AmazonLinux 2023 aarch64 (aarch64-aws2023-linux-gnu-glibc-2.34-gcc-11.tar.gz)
- Target: RHEL 8 aarch64 (aarch64-rhel8-linux-gnu-glibc-2.28-gcc-8.tar.gz)
- Target: RHEL 9 aarch64 (aarch64-rhel9-linux-gnu-glibc-2.34-gcc-11.tar.gz)

All toolchain's host platform is modern Linux x86_64 OS, typically Ubuntu 22.04 is tested.

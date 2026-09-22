# CachyOS DCN32 Test Kernel

Unofficial test build of the CachyOS Linux kernel with a proposed fix for the
AMD DCN32 `dcn32_program_compbuf_size` timeout.

This build is intended for debugging and testing the display issues described
in the related upstream GitHub issue.

## Kernel base

This kernel is based on:

- Linux: `7.3-rc3`
- CachyOS release: `cachyos-7.3-rc3-1`
- Architecture: `x86_64`
- Compiler: Clang 22.1.8
- Linker: LLD 22.1.8

Kernel name:

```text
linux-cachyos-dcn32

Checksums:

e60d754e68a67370fa761fd6c0242b4beadb3198b06fc16930bcb04c96201be7  linux-cachyos-dcn32-7.3.rc3-1-x86_64.pkg.tar.zst
3fc9c7aef1176a6160aaa682a3fd0365a8edac4f8e09c62a0062a39a1d747dfd  linux-cachyos-dcn32-headers-7.3.rc3-1-x86_64.pkg.tar.zst

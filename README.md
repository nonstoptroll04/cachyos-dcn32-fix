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

Kernel release:

```text
linux-cachyos-dcn32

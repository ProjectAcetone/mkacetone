# Acetone build system

## Supported devices for Acetone-EFI:

- `generic_x86`: Aya Neo Air and Aya Neo Next

## Supported devices for Acetone-U-Boot(TODO):

- `odroidgo2`: Odroid Go Advance(Black edition too)

## Acetone-EFI:

Mostly compatible with [The Boot Loader Specification](https://systemd.io/BOOT_LOADER_SPECIFICATION/) entries
Also supports booting into other bootloaders, specified in BootXXXX Efi variables

### Build requirements:
- Everything to build Linux kernel
- Rust nightly `x86_64-unknown-linux-musl` toolchain + `cargo`
- `cpio`, `fakeroot` and coreutils

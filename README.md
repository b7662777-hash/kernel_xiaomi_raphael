# Xiaomi Raphael Kernel

Linux kernel source maintained for the Xiaomi Redmi K20 Pro / Mi 9T Pro (`raphael`). The repository tracks the `16` branch.

## Device

- **Device:** Xiaomi Redmi K20 Pro / Mi 9T Pro
- **Codename:** `raphael`
- **SoC:** Qualcomm Snapdragon 855
- **Branch:** `16`

## Purpose

This repository provides the kernel source used as part of an Android platform build for the `raphael` device. It is intended to be integrated with the corresponding Android device tree, vendor tree, and platform manifest.

## Build Context

A kernel tree is not normally built as a standalone Android application. Build configuration, defconfig, toolchain, Android version, and output target depend on the ROM/device source tree using this repository.

Before building, verify the matching device configuration and kernel build instructions in the ROM source tree.

## Repository Note

This repository contains device-specific Android kernel source. Keep changes reproducible and document non-upstream patches clearly when maintaining a custom kernel tree.

## License

Kernel files retain the licenses specified in their respective source files. See the repository's license and source headers for applicable terms.

# nanobyte_os

OS tutorial from the Nanobyte YouTube channel  
This repository contains the code and build scripts for the “Building an OS” series by Nanobyte.

---

## Table of Contents

- [About](#about)  
- [Features](#features)  
- [Prerequisites](#prerequisites)  


---

## About

nanobyte_os is a tutorial-driven operating system project, where each chapter or video in the “Building an OS” series adds features, components, or modules. It’s intended to demystify how an OS works from low-level to higher-level abstractions.

---

## Features

Here are typical components and features included (depending on the current progress in the series):

- Bootloader  
- Kernel (interrupts, memory management, multitasking)  
- Device drivers (keyboard, disk, etc.)  
- File system implementation  
- Support for running in QEMU or real hardware  
- Toolchain building (cross-compiler, binutils)  
- Automation of build steps via SCons / scripts  

---

## Prerequisites

You’ll need a development environment with tools to build OS code and simulate/boot it.

### On Ubuntu / Debian:

```bash
sudo apt update
sudo apt install build-essential bison flex libgmp3-dev libmpc-dev libmpfr-dev texinfo wget \
    nasm mtools python3 python3-pip python3-parted scons dosfstools libguestfs-tools qemu-system-x86

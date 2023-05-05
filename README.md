# Prepare RISC-V Toolchain and QEMU #

## Prerequisites ##

Please make sure that you have the following dependencies installed on your system.
- working C++ compiler
- git
- cmake
- ninja
- wget
- tar

## Build & Install RISC-V GNU Toolchain ##

To build and install the RISC-V GNU toolchain, please follow the official [instructions](https://github.com/riscv/riscv-gnu-toolchain).

## Download Clang Toolchain & Build Cross Compiler ##

To download the clang toolchain and build a cross compiler for the RISC-V target, please follow the official instructions provided by the [LLVM project](https://github.com/llvm/llvm-project/).

## Build riscv64 Linux User Mode QEMU ##

To build the riscv64 linux user mode QEMU, please follow the official [instructions](https://github.com/qemu/qemu) provided by the QEMU project.
You can download the latest QEMU source code from the QEMU [download page](https://download.qemu.org).

## Example ##

You can refer to `prepare_riscv_toolchain_qemu.sh` to prepare the RISC-V toolchain and QEMU, modifying the content (e.g., toolchain version) if necessary.

We also provide the prebuilt toolchain and qemu, download them from [the release page](https://github.com/sifive/prepare-riscv-toolchain-qemu/releases), and enjoy using them!

## References ##

See instructions in the following links for more details:

* [Clang getting started](https://clang.llvm.org/get_started.html)
* [RISC-V GNU toolchain](https://github.com/riscv/riscv-gnu-toolchain)
* [QEMU](https://github.com/qemu/qemu)
* [RISC-V Linux QEMU](https://risc-v-getting-started-guide.readthedocs.io/en/latest/linux-qemu.html)

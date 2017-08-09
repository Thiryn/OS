# OS
Exploration of a operating system creation

Exploring the creation of an operating system following "Writing a Simple Operating System", by Nick Blundell

The aim of this project is just exploration and in the end the implementation of the network stack of a linux OS
## Requirements
* QEmu
* nasm
## Usage
To build the image :
```bash
$> nasm boot_sect.asm -f bin -o boot_sect.bin
```
To run the image :
```bash
$> qemu-system-x86_64 boot_sect.bin
```
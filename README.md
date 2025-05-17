# My Mini Operating System

This is a barebones 32-bit operating system built from scratch using x86 Assembly and C, designed to demonstrate the fundamental concepts of how a computer boots and runs an OS without relying on existing operating systems or libraries.

## 🛠Features
- Boots with [GRUB](https://www.gnu.org/software/grub/)
- Uses a custom Multiboot-compliant header
- Freestanding kernel written in C
- Direct screen output using VGA text buffer
- Runs on QEMU or real hardware (via bootable ISO)

- 
## Folder Structure
my-mini-os/
├── boot.asm # Entry point assembly code
├── kernel.c # Main kernel logic
├── linker.ld # Memory layout and linker script
├── Makefile # Build automation
├── iso/
│ └── boot/
│ ├── grub/
│ │ └── grub.cfg
│ └── kernel.bin
└── my-mini-os.iso # Bootable image

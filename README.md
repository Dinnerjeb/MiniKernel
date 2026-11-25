# MiniKernel

**A small operating system kernel built from scratch.**

MiniKernel is an experimental hobby operating system project focused on learning low-level programming, kernel development, and computer architecture.

The project is being developed from the ground up as a way to explore how operating systems work at a fundamental level.

> **Experimental Project**
>
> MiniKernel is currently in an early development stage. It is not ready for daily use and may contain bugs or incomplete features.

## Features

Currently implemented:

- **Kernel startup** – Boots into the custom kernel.
- **Memory information** – Displays available memory information.
- **Command interface** – A simple text-based command system.
- **Reboot** – Restarts the system.
- **Help system** – Lists available commands.
- **About command** – Displays information about the project and its pangolin mascot.

## Available Commands

| Command | Description |
|---|---|
| `help` | Displays available commands |
| `mem` | Shows memory information |
| `about` | Displays kernel information |
| `reboot` | Restarts the system |

## Running OpenKernelOS

You can run the bootable ISO using a virtual machine.

For example, with QEMU:

```bash
qemu-system-x86_64 -cdrom minikernel.iso
```

You can also use VirtualBox or other virtualization software that supports bootable ISO images.

**Note:** Running experimental operating systems in a virtual machine is recommended.

## Development Goals

Planned areas of development:

- [ ] Memory management
- [ ] Interrupt handling
- [ ] Keyboard input improvements
- [ ] Filesystem support
- [ ] Process management
- [ ] Basic hardware interaction
- [ ] More kernel commands
- [ ] Improved terminal interface

These are development goals, not currently implemented features.

## Philosophy

MiniKernel is built around a simple idea:

**Understand computers by building the software that runs them.**

Rather than relying entirely on existing operating systems, this project explores the foundations of computing one component at a time.

## Screenshots

Screenshots of the kernel and its command interface will be added as development progresses.

## Project Status

- Version: `0.1`
- Stage: Experimental / Early Development
- Architecture: x86-64
- Bootable ISO: Available

## License

License information will be added.

---

**Built with curiosity and a pangolin. 🐾**

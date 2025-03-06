# ISA Labs

> A collection of Bare Metal `ISA / Hardware` Programming projects.

![logo](logo.jpg)

QA:

- [How to run a program without an operating system?](https://stackoverflow.com/questions/22054578/how-to-run-a-program-without-an-operating-system/32483545#32483545)
- ...

## Dependencies

> Before you begin, make sure all required dependencies are installed to ensure smooth compilation and execution.

- 🔧 Run `./configure` to check and configure the environment.

## Build

> Each `.S` file on the top-level is an operating system! It gets compiled to a corresponding `.img` file.

```bash
make
```

## Run

Run the default OS on QEMU:

```bash
./run
```

Run a given OS:

```bash
./run bios_hello_world
./run bios_putc
```

## Feature Work

> This section outlines the upcoming tasks and improvements that are planned for the project. These features aim to enhance project organization, streamline the virtualization process, and improve the documentation for better usability.

- 📂 Create a separate directory for each project.
- 🖥️ Limit support to QEMU for virtualization.
- 📚 Improve documentation in Markdown format (.md).

## References

- [linux-kernel-module-cheat](https://github.com/cirosantilli/linux-kernel-module-cheat)
- ...

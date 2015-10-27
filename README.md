# x86 Bare Metal Examples

Minimal operating systems to learn low level programming.

1.  [Getting started](getting-started.md)
1.  [About](about.md)
1.  Examples
    1.  [printf](printf/)
    1.  [min](min.S)
    1.  [No ld script](no-ld-script/)
    1.  BIOS
        1.  [one char](bios_one_char.S)
        1.  [hello world](bios_hello_world.S)
            1.  [NASM](nasm/)
        1.  [newline](bios_newline.S)
        1.  [carriage return](bios_carriage_return.S)
        1.  [cursor position](bios_cursor_position.S)
        1.  [color](bios_color.S)
        1.  [background](bios_background.S)
        1.  [scroll](bios_scroll.S)
            1.  [clear screen](bios_clear_screen.S)
        1.  [pixel](bios_pixel.S)
            1.  [pixel line](bios_pixel_line.S)
        1.  [keyboard](bios_keyboard.S)
            1.  [keyboard loop](bios_keyboard_loop.S)
        1.  [disk load](bios_disk_load.S)
            1.  [disk load 2](bios_disk_load2.S)
        1.  [detect memory](bios_detect_memory.S)
    1.  [Initial state](initial_state.S)
    1.  [reboot](reboot.S)
    1.  [Not testable in userland](not-testable-in-userland.md)
        1.  [Segment registers](segment_registers.S)
            1.  [SS](ss.S)
            1.  [CS](cs.S)
        1.  [Interrupt](interrupt.S)
            1.  [int $1](interrupt1.S)
            1.  [Interrupt zero divide](interrupt_zero_divide.S)
            1.  [Interrupt loop](interrupt_loop.S)
        1.  in
            1.  [in keyboard](in_keyboard.S)
            1.  [in RTC](in_rtc.S)
            1.  [in PIT (TODO)](in_pit.S)
            1.  [in beep](in_beep.S)
            1.  [in beep_illinois](in_beep_illinois.S)
            1.  [in mouse (TODO)](in_mouse.S)
        1.  [Protected mode](protected_mode.S)
            1. [Segment base (TODO)](segment_base.S)
            1. [IDT](idt.S)
                1. [IDT zero divide](idt_zero_divide.S)
                1. IDT PIT
            1. Segmentation fault handler: memory bound, ring, RWX violations
            1. [Paging](paging.S)
    1.  APM
        1.  [APM shutdown](apm_shutdown.S)
        1.  [APM shutdown 2](apm_shutdown2.S)
    1.  [Multiboot](multiboot/)
    1.  [GRUB](grub/)
    1.  TODO not working
        1. [UEFI](uefi/)
    1.  Misc
        1.  [hajji](hajji/)
1.  Tests
    1. [PRINT_BYTES](test_print_bytes.S)
1.  Theory
    1.  [Modes of operation](modes-of-operation.md)
        1.  [Segmentation](segmentation.md)
    1.  [Formats](formats.md)
        1.  [MBR](mbr.md)
    1.  [IO](io.md)
        1.  [BIOS](bios.md)
        1.  [APM](apm.md)
    1.  [Debug](debug.md)
    1.  [Bibliography](bibliography.md)
1.  [TODO](TODO.md)

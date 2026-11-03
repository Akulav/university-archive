# Basic x86 Assembler

Low-level experiments in 16-bit x86 assembly: a bootloader, a tiny kernel and a lexer for a small custom language.

## Structure

| Folder | Description |
| --- | --- |
| `Assembler/Bash` | Bootloader plus a kernel with a minimal shell-like prompt that reads keyboard input |
| `Assembler/Draw` | Bootloader plus a kernel that draws to the screen |
| `Lexer` | `Lexer.asm` and the grammar (`grammar.txt`) of a toy language, with a factorial example |

## Requirements

- [NASM](https://www.nasm.us/)
- [QEMU](https://www.qemu.org/) (`qemu-system-x86_64`)
- A Unix shell (Linux or WSL)

## Running

From `Assembler/Bash` or `Assembler/Draw`, run the `FULL` script. It assembles the bootloader and kernel, builds a floppy image and boots it in QEMU:

```bash
cd Assembler/Bash
sh FULL
```

The other helper scripts (`BIN`, `IMG`, `MountIMG`, `COMPLETE-LOAD`, `appender.sh`) run the individual build steps.

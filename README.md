# `whoami`

```asm
mov     rdi, [social_interaction]
call    drain_battery

cmp     rax, 0
je      trigger_shutdown

mov     rdi, [curiosity]
call    investigate
```

Hi, I'm **Ravindu**.

I like understanding software from the layer where the documentation stops being helpful.

Mostly interested in:

* Linux internals
* Reverse engineering
* x86-64 assembly
* Kernel security
* eBPF
* Low-level debugging

### What I do

I tend to start with a simple question:

> **"What actually happens here?"**

Then I follow it.

Source → compiler → assembly → registers → kernel API → memory → runtime behavior.

I use tools like `GDB`, `radare2`, `LLVM`, `objdump`, `readelf`, `pahole`, `bpftool`, `QEMU`, and whatever else helps me see what's actually happening.

### Currently exploring

```text
Linux kernel internals
├── memory management
├── SLUB / kmalloc
├── kernel modules
└── eBPF

Reverse engineering
├── ELF
├── relocations
├── assembly
└── dynamic analysis
```

Some of this work is public here.
Some of it is still sitting somewhere between **"interesting idea"** and **"okay, this needs another 20 hours."** 😂

### Philosophy

I don't particularly care about knowing that a function works.

I want to know **why it works, where the data goes, and what the CPU actually does.**

```assembly
mov  rdi, [social_interaction]
call drain_battery           ; Decrements remaining social energy

cmp  rax, 0x0                ; Check if battery == depleted
je   trigger_shutdown

mov  rdi, small_talk
call panic                   ; Kernel panic: Illegal instruction
jmp  [hermit_mode]           ; Retreat to localhost immediately
```
- Reverse engineer focused on Linux kernel internals, low-level security, x86_64, and understanding what actually happens beneath the abstraction.

# About ekknod
Researching computer cheats as a hobby.  

Anti-Cheating and cheating are actually the very same thing, i don't pick sides. both requires the same creativity.  
Both are cool up to certain point. VAC/EAC/Vanguard are good examples of cool anti-cheats, because they are less likely to harm non cheating players.
Obviously no cheat / anti-cheat is perfect.

To clarify more, I know people who got banned from MW2 (**RICOCHET Anti-Cheat**),  
without ever cheating in that game just by having tools installed that could be used for cheating.  
That's like accusing woodsman of a murder that didn't happen, because he owns axe.


# Memory Access  
**EFI**: [SubGetVariable](https://github.com/ekknod/SubGetVariable) - infects DXE bios image with backdoor before boot.  
**EFI**: [EC](https://github.com/ekknod/EC) - CS:GO cheat (EFI/DMA/Kernel/Usermode)  
**FPGA**: [pcileech-wifi](https://github.com/ekknod/pcileech-wifi) - FPGA card looks like a wireless adapter, but hides inside [pcileech-fpga](https://github.com/ufrisk/pcileech-fpga) researching tool.  
**SMM**: [smm](https://github.com/ekknod/smm) - modified SMM bios image manipulates CS2 cvar on system sleep mode [(see video)](https://streamable.com/58y7zz).  
**Vulnerable Driver**: [AmdRyzenMasterCheat](https://github.com/ekknod/AmdRyzenMasterCheat) - remote access tool inside AmdRyzenMaster utility   [(see video)](https://www.youtube.com/video/l91pJW86KEQ).  
**UM**: [SetWindowHookEx](https://github.com/ekknod/SetWindowHookEx) - executes vulnerable routines inside CS:GO to enable wallhack.  

# Mouse Input
**UM**: [logitech-cve](https://github.com/ekknod/logitech-cve) - uses logitech virtual driver for mouse input  
**KM**: [MouseClassServiceCallbackTrick](https://github.com/ekknod/MouseClassServiceCallbackTrick) - spoofs _ReturnAddress() to get through Anti-Cheat hook.  
**KM**: [MouseClassServiceCallbackMeme](https://github.com/ekknod/MouseClassServiceCallbackMeme) - rewrites mouse callback to completely circuivement Anti-Cheat hook.  
**KM**: [acdrv](https://github.com/ekknod/acdrv) - trying to detect kernel mouse input manipulation  
**UM**: [ec-guard](https://github.com/ekknod/ec-guard) - trying to detect usermode mouse input manipulation  

# General cool projects
**EFI**: [efi-monitor](https://github.com/ekknod/efi-monitor) - hooking ntoskrnl.exe before launch  
**Utility**: [drvscan](https://github.com/ekknod/drvscan) - tool for scanning memory/PCI/EFI  

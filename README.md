# rtl8672-toolchain
RTL8672 compatible build chain source code.  Should work with all Lexras,
not just the chip found in the RTL8672.

The RTL8672 CPU-identifies as a MIPS R3000, but is actually a Lexra, aka MIPS minus unaligned stores and loads.

    # cat /proc/cpuinfo
    
    system type             : RTL8672
    
    processor               : 0
    
    cpu model               : R3000 V0.0```

I've extracted this from the GPL source code released by TRENDnet, as the source code to the toolchain was rather difficult to find (lots of binaries that did not work well with the environments I was trying to compile and run in (mostly the latter).

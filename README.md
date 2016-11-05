# rtl8672-toolchain
RTL8672 compatible build chain source code.  Should work with all Lexras,
not just the chip found in the RTL8672.

The RTL8672 CPU-identifies as a MIPS R3000, but is actually a Lexra, aka MIPS minus unaligned stores and loads.

    # cat /proc/cpuinfo
    
    system type             : RTL8672
    
    processor               : 0
    
    cpu model               : R3000 V0.0```

I've extracted this from the GPL source code released by TRENDnet, as the source code to the toolchain was rather difficult to find (lots of binaries that did not work well with the environments I was trying to compile and run in (mostly the latter).

References:
http://web.archive.org/web/20140314145913/http://jonahprobell.com/lexra.html

https://wikidevi.com/wiki/Realtek#xDSL and https://wikidevi.com/wiki/Lexra_LX5280

https://github.com/KrabbyPatty/rtl819x-toolchain/blob/master/toolchain/rsdk-1.5.5-5281-EB-2.6.30-0.9.30.3-110714/RELEASE.NOTE

https://github.com/KrabbyPatty/rtl819x-toolchain/blob/master/toolchain/rsdk-1.5.5-5281-EB-2.6.30-0.9.30.3-110714/userguide.pdf

http://rtl8181.sourceforge.net/rtl8181_toolchain.php

https://pigworlds.wordpress.com/2011/05/29/tew-652brp-v2-toolchain/

http://www.trendnet.com/downloads/list_gpl.asp

https://sourceforge.net/projects/rtl819x/files/

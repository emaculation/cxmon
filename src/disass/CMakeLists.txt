
SET(disass_STAT_SRCS
   ansidecl.h
   bfd.h
   dis-asm.h
   floatformat.c
   floatformat.h
   i386-dis.c
   m68k-dis.c
   m68k-opc.c
   m68k.h
   opintl.h
   ../sysdeps.h
)

ADD_LIBRARY(disass STATIC ${disass_STAT_SRCS})

add_subdirectory(disass)

SET(cxmon_SRCS
   main.cpp
   mon.cpp
   mon.h
   mon_6502.cpp
   mon_z80.cpp
   mon_atraps.h
   mon_cmd.cpp
   mon_cmd.h
   mon_disass.cpp
   mon_disass.h
   mon_lowmem.cpp
   mon_lowmem.h
   mon_ppc.cpp
   sysdeps.h
)

INCLUDE_DIRECTORIES(../)

add_executable(cxmon ${cxmon_SRCS})

target_link_libraries(cxmon disass)

install(TARGETS cxmon RUNTIME DESTINATION bin)


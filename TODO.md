* Test using `-fdata-sections -ffunction-sections -Wl,--gc-sections` in CFLAGS/LDFLAGS
* Add better testing for each syscall
* Implement 64-bit returning syscalls
* Consider implementing a __RT0_WITH_FASTER_SYSCALL__ (more register/stack efficient versions that will result in larger binaries)
* Consider implementing an rt0-cc driver script
* Add clibs support
* Consider implementing some subset of the Newlib porting functions
* Consider implementing some subset of stdlib.h
* Consider implementing some subset of unistd.h
* Consider implementing Thread Local Storage POSIX interfaces
* Consider implementing C++ constructor/destructor setups
* Consider implementing more featureful/accurate FreeBSD implementation
* Work on making FreeBSD support more complete & work OOTB
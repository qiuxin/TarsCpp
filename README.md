# Tars Cpp Arm version 

Note well:  This is Arm verion!

# Modifications
To make Tars run well on Arm platform,  the following modifications are made:

## Update the files itemized blow:

/TarsCpp/util/include/util/tc_atomic.h

/TarsCpp/util/include/util/tc_fcontext.h

/TarsCpp/util/include/util/tc_timeprovider.h

/TarsCpp/util/src/CMakeLists.txt

/TarsCpp/util/src/tc_timeprovider.cpp


## Add new files itemized blow:

/TarsCpp/util/include/util/tc_fcontext_aarch64.h

/TarsCpp/util/src/tc_jump_aarch64_sysv_elf_gas.s

/TarsCpp/util/src/tc_make_aarch64_sysv_elf_gas.s


# Dependent environment

Software |version requirements
------|--------
linux kernel:   |	2.6.18 and above
gcc:          	|   4.1.2 and above glibc-devel
bison tool:     |	2.5 and above
flex tool:      |	2.5 and above
cmake:       	|   2.8.8 and above
mysql:          |	4.1.17 and above

# Compile and install
```
git clone https://github.com/TarsCloud/TarsCpp.git --recursive
cd TarsCpp
cmake .
make
make install
```

Detailed installation reference Install.md under https://github.com/TarsCloud/Tars.git

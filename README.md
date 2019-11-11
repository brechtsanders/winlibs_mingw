# MinGW-w64 - winlibs standalone build
The winlibs standalone build of GCC compiler and MinGW-w64.
GCC is a free and open source C/C++ compiler.
MinGW-w64 is a free and open source for targetting Windows 32-bit and 64-bit platforms with C/C++ compilers.
The combination of both gives you a free C/C++ compiler for Windows.

Additional tools are added to this build including:
- GDB - the GNU Project debugger
- GNU Binutils
- GNU Make

The i686 download is the 32-bit version, which runs natively on and compiles for Windows 32-bit (of course it also runs on 64-bit).

The x86_64 download is the 64-bit version, which runs natively on and compiles for Windows 64-bit.

The ultimate goal of winlibs is to also provide libraries built with this compiler, in order to provide a comprehensive C/C++ development environment, with the following goals in mind:
- provide both static and shared libraries where possible
- focus on production quality (no debug versions of libraries and debugging information stripped from binaries)
- useability from the MSYS 2 shell aswell as from IDEs like Code::Blocks

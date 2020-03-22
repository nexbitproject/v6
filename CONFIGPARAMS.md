`configure' configures nexbit Core 4.0.99 to adapt to many kinds of systems.

Usage: ./configure [OPTION]... [VAR=VALUE]...

To assign environment variables (e.g., CC, CFLAGS...), specify them as
VAR=VALUE.  See below for descriptions of some of the useful variables.

Defaults for the options are specified in brackets.

Configuration:
  -h, --help              display this help and exit
      --help=short        display options specific to this package
      --help=recursive    display the short help of all the included packages
  -V, --version           display version information and exit
  -q, --quiet, --silent   do not print `checking ...' messages
      --cache-file=FILE   cache test results in FILE [disabled]
  -C, --config-cache      alias for `--cache-file=config.cache'
  -n, --no-create         do not create output files
      --srcdir=DIR        find the sources in DIR [configure dir or `..']

Installation directories:
  --prefix=PREFIX         install architecture-independent files in PREFIX
                          [/usr/local]
  --exec-prefix=EPREFIX   install architecture-dependent files in EPREFIX
                          [PREFIX]

By default, `make install' will install all the files in
`/usr/local/bin', `/usr/local/lib' etc.  You can specify
an installation prefix other than `/usr/local' using `--prefix',
for instance `--prefix=$HOME'.

For better control, use the options below.

Fine tuning of the installation directories:
  --bindir=DIR            user executables [EPREFIX/bin]
  --sbindir=DIR           system admin executables [EPREFIX/sbin]
  --libexecdir=DIR        program executables [EPREFIX/libexec]
  --sysconfdir=DIR        read-only single-machine data [PREFIX/etc]
  --sharedstatedir=DIR    modifiable architecture-independent data [PREFIX/com]
  --localstatedir=DIR     modifiable single-machine data [PREFIX/var]
  --runstatedir=DIR       modifiable per-process data [LOCALSTATEDIR/run]
  --libdir=DIR            object code libraries [EPREFIX/lib]
  --includedir=DIR        C header files [PREFIX/include]
  --oldincludedir=DIR     C header files for non-gcc [/usr/include]
  --datarootdir=DIR       read-only arch.-independent data root [PREFIX/share]
  --datadir=DIR           read-only architecture-independent data [DATAROOTDIR]
  --infodir=DIR           info documentation [DATAROOTDIR/info]
  --localedir=DIR         locale-dependent data [DATAROOTDIR/locale]
  --mandir=DIR            man documentation [DATAROOTDIR/man]
  --docdir=DIR            documentation root [DATAROOTDIR/doc/nexbit]
  --htmldir=DIR           html documentation [DOCDIR]
  --dvidir=DIR            dvi documentation [DOCDIR]
  --pdfdir=DIR            pdf documentation [DOCDIR]
  --psdir=DIR             ps documentation [DOCDIR]

Program names:
  --program-prefix=PREFIX            prepend PREFIX to installed program names
  --program-suffix=SUFFIX            append SUFFIX to installed program names
  --program-transform-name=PROGRAM   run sed PROGRAM on installed program names

System types:
  --build=BUILD     configure for building on BUILD [guessed]
  --host=HOST       cross-compile to build programs to run on HOST [BUILD]

Optional Features:
  --disable-option-checking  ignore unrecognized --enable/--with options
  --disable-FEATURE       do not include FEATURE (same as --enable-FEATURE=no)
  --enable-FEATURE[=ARG]  include FEATURE [ARG=yes]
  --enable-silent-rules   less verbose build output (undo: "make V=1")
  --disable-silent-rules  verbose build output (undo: "make V=0")
  --disable-maintainer-mode
                          disable make rules and dependencies not useful (and
                          sometimes confusing) to the casual installer
  --enable-dependency-tracking
                          do not reject slow dependency extractors
  --disable-dependency-tracking
                          speeds up one-time build
  --enable-shared[=PKGS]  build shared libraries [default=yes]
  --enable-static[=PKGS]  build static libraries [default=yes]
  --enable-fast-install[=PKGS]
                          optimize for fast installation [default=yes]
  --disable-libtool-lock  avoid locking (might break parallel builds)
  --disable-wallet        disable wallet (enabled by default)
  --enable-upnp-default   if UPNP is enabled, turn it on at startup (default
                          is no)
  --disable-tests         do not compile tests (default is to compile)
  --disable-gui-tests     do not compile GUI tests (default is to compile if
                          GUI and tests enabled)
  --disable-bench         do not compile benchmarks (default is to compile)
  --enable-extended-functional-tests
                          enable expensive functional tests when using lcov
                          (default no)
  --disable-hardening     do not attempt to harden the resulting executables
                          (default is to harden when possible)
  --enable-reduce-exports attempt to reduce exported symbols in the resulting
                          executables (default is no)
  --disable-ccache        do not use ccache for building (default is to use if
                          found)
  --enable-lcov           enable lcov testing (default is no)
  --enable-lcov-branch-coverage
                          enable lcov testing branch coverage (default is no)
  --enable-glibc-back-compat
                          enable backwards compatibility with glibc
  --enable-asm            Enable assembly routines (default is yes)
  --disable-zmq           disable ZMQ notifications
  --disable-man           do not install man pages (default is to install)
  --enable-debug          use debug compiler flags and macros (default is no)
  --enable-gprof          use gprof profiling compiler flags (default is no)
  --enable-werror         Treat certain compiler warnings as errors (default
                          is no)
  --disable-largefile     omit support for large files

Optional Packages:
  --with-PACKAGE[=ARG]    use PACKAGE [ARG=yes]
  --without-PACKAGE       do not use PACKAGE (same as --with-PACKAGE=no)
  --with-pic[=PKGS]       try to use only PIC/non-PIC objects [default=use
                          both]
  --with-aix-soname=aix|svr4|both
                          shared library versioning (aka "SONAME") variant to
                          provide on AIX, [default=aix].
  --with-gnu-ld           assume the C compiler uses GNU ld [default=no]
  --with-sysroot[=DIR]    Search for dependent libraries within DIR (or the
                          compiler's sysroot if not specified).
  --with-miniupnpc        enable UPNP (default is yes if libminiupnpc is
                          found)
  --with-qtcharts         enable qtcharts support (default is yes if qt is
                          enabled and qtchartview is found)
  --with-system-univalue  Build with system UniValue (default is no)
  --with-zerocoin-bignum=gmp|openssl|auto
                          Specify Bignum Implementation. Default is auto
  --with-protoc-bindir=BIN_DIR
                          specify protoc bin path
  --with-sanitizers       comma separated list of extra sanitizers to build
                          with (default is none enabled)
  --with-utils            build nexbit-cli nexbit-tx (default=yes)
  --with-libs             build libraries (default=no)
  --with-daemon           build nexbitd daemon (default=yes)
  --with-incompatible-bdb allow using a bdb version other than 4.8
  --with-gui[=no|qt5|auto]
                          build nexbit-qt GUI (default=auto)
  --with-qt-incdir=INC_DIR
                          specify qt include path (overridden by pkgconfig)
  --with-qt-libdir=LIB_DIR
                          specify qt lib path (overridden by pkgconfig)
  --with-qt-plugindir=PLUGIN_DIR
                          specify qt plugin path (overridden by pkgconfig)
  --with-qt-translationdir=PLUGIN_DIR
                          specify qt translation path (overridden by
                          pkgconfig)
  --with-qt-svgdir=PLUGIN_DIR
                          specify qt svg path (overridden by pkgconfig)
  --with-qt-bindir=BIN_DIR
                          specify qt bin path
  --with-qtdbus           enable DBus support (default is yes if qt is enabled
                          and QtDBus is found)
  --with-boost[=ARG]      use Boost library from a standard location
                          (ARG=yes), from the specified location (ARG=<path>),
                          or disable it (ARG=no) [ARG=yes]
  --with-boost-libdir=LIB_DIR
                          Force given directory for boost libraries. Note that
                          this will override library path detection, so use
                          this parameter only if default library detection
                          fails and you know exactly where your boost
                          libraries are located.
  --with-boost-system[=special-lib]
                          use the System library from boost - it is possible
                          to specify a certain library for the linker e.g.
                          --with-boost-system=boost_system-gcc-mt
  --with-boost-filesystem[=special-lib]
                          use the Filesystem library from boost - it is
                          possible to specify a certain library for the linker
                          e.g. --with-boost-filesystem=boost_filesystem-gcc-mt
  --with-boost-program-options[=special-lib]
                          use the program options library from boost - it is
                          possible to specify a certain library for the linker
                          e.g.
                          --with-boost-program-options=boost_program_options-gcc-mt-1_33_1
  --with-boost-thread[=special-lib]
                          use the Thread library from boost - it is possible
                          to specify a certain library for the linker e.g.
                          --with-boost-thread=boost_thread-gcc-mt
  --with-boost-chrono[=special-lib]
                          use the Chrono library from boost - it is possible
                          to specify a certain library for the linker e.g.
                          --with-boost-chrono=boost_chrono-gcc-mt
  --with-boost-unit-test-framework[=special-lib]
                          use the Unit_Test_Framework library from boost - it
                          is possible to specify a certain library for the
                          linker e.g.
                          --with-boost-unit-test-framework=boost_unit_test_framework-gcc
=========================================================
NBC_PARAMS= ./configure --prefix=`pwd`/depends/i686-w64-mingw32 --with-incompatible-bdb --with-gui=qt5

./configure --prefix=`pwd`/depends/x86_64-w64-mingw32 --with-gui=qt5
config for win build
CONFIG_SITE=$PWD/depends/x86_64-w64-mingw32/share/config.site ./configure --prefix=/
CONFIG_SITE=$PWD/depends/i686-w64-mingw32/share/config.site ./configure --prefix=/ --disable-wallet

SUpported PARAMS:     make HOST=x86_64-w64-mingw32 -j4

A prefix will be generated that's suitable for plugging into Bitcoin's
configure. In the above example, a dir named x86_64-w64-mingw32 will be
created. To use it for Bitcoin:

    ./configure --prefix=`pwd`/depends/x86_64-w64-mingw32

Common `host-platform-triplets` for cross compilation are:

- `i686-w64-mingw32` for Win32
- `x86_64-w64-mingw32` for Win64
- `x86_64-apple-darwin14` for macOS
- `arm-linux-gnueabihf` for Linux ARM 32 bit
- `aarch64-linux-gnu` for Linux ARM 64 bit
- `riscv32-linux-gnu` for Linux RISC-V 32 bit
- `riscv64-linux-gnu` for Linux RISC-V 64 bit

# Awesome userland tools

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Unix core utilities

### BSD versions

* DragonFly BSD
* FreeBSD
* NetBSD
* OpenBSD

### GNU/Linux versions

* coreutils
* diffutils
* findutils
* util-linux

### Low-memory versions

* [BusyBox](https://www.busybox.net)
* [Toybox](https://www.landley.net/toybox/)
* [suckless base](https://core.suckless.org/sbase/)
* [Heirloom Project](http://heirloom.sourceforge.net)

### Versions written in memory-safe languages

* [go-coreutils](https://github.com/aisola/go-coreutils) (Go)
* [mesabox](https://github.com/mesalock-linux/mesabox) (Rust)
* [uutils](https://github.com/uutils) (Rust)

## Shells

### Bourne-compatible shells

* [**sh**](https://pubs.opengroup.org/onlinepubs/9699919799/utilities/sh.html) (POSIX shell)
* [**bash**](https://www.gnu.org/software/bash/) (GNU Bourne-again shell)
* [ash](https://www.in-ulm.de/~mascheck/various/ash/) (Almquist shell)
* [dash](http://gondor.apana.org.au/~herbert/dash/) (Debian Almquist shell)
* [ksh93](http://www.kornshell.com/doc/ksh93.html) (Korn shell)
* [pdksh](https://linux.die.net/man/1/pdksh) (Public domain Korn shell)
* [mksh](http://www.mirbsd.org/mksh.htm) (MirBSD ksh)
* [zsh](https://www.zsh.org) (Z shell)

### Other Unix shells

* [rc](http://man.cat-v.org/plan_9/1/rc) (Plan 9 shell)
* [BSD csh](https://en.wikipedia.org/wiki/C_shell) (C Shell)
* [tcsh](https://www.tcsh.org) (TENEX-inspired C shell)
* [fish](https://fishshell.com) (Friendly interactive shell)

### Windows/DOS shells

* `command.com` (MS-DOS shell)
* [FreeCOM](http://wiki.freedos.org/wiki/index.php/FreeCOM) (FreeDOS version of `command.com`)
* [Microsoft Windows command interpreter](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/cmd) (`cmd.exe`, `.bat`)
* [Microsoft PowerShell](https://docs.microsoft.com/en-us/powershell/) (`pwsh`, `.ps1`)

## Other de facto standard tools

### Runoff family text formatters

* groff
* mandoc
* nroff
* troff

### Awk language interpreters

* One true awk
* Mawk
* Nawk
* Gawk

### Lex/yacc parser generators

* Lex
* Flex
* Bison

### Compression and archiving

* [bzip2](https://sourceware.org/bzip2/)
* compress
* [gzip](http://www.gzip.org)
* tar
* [xz](https://tukaani.org/xz/)

### Internet

* [bind-utils](http://www.linuxfromscratch.org/blfs/view/svn/basicnet/bind-utils.html) (DNS)

### Other

* file -- [darwinsys](https://www.darwinsys.com/file/), [OpenBSD](http://man.openbsd.org/file)
* [patch](https://savannah.gnu.org/projects/patch/)
* rsync -- [original](https://rsync.samba.org), [OpenBSD](https://www.openrsync.org)
* ssh, scp -- [OpenSSH](https://www.openssh.com)

## C standard library

* [GNU libc](https://www.gnu.org/software/libc/) (aka `glibc`)
* BSD libc
  * [DragonFly BSD](https://gitweb.dragonflybsd.org/dragonfly.git/tree/HEAD:/lib/libc)
  * [FreeBSD](https://svnweb.freebsd.org/base/head/lib/libc/)
  * [NetBSD](http://cvsweb.netbsd.org/bsdweb.cgi/src/lib/libc/?only_with_tag=MAIN)
  * [OpenBSD](https://cvsweb.openbsd.org/src/lib/libc/)
* Lightweight
  * [Bionic libc](https://android.googlesource.com/platform/bionic/+/master/libc/)
  * [musl libc](https://musl.libc.org)
  * [diet libc](https://www.fefe.de/dietlibc/)
  * [uClibc](https://uclibc.org)
  * [Newlib](https://en.wikipedia.org/wiki/Newlib)

This directory contains the sources of the GNU C Library.
See the file "version.h" for what release version you have.

The GNU C Library is the standard system C library for all GNU systems,
and is an important part of what makes up a GNU system.  It provides the
system API for all programs written in C and C-compatible languages such
as C++ and Objective C; the runtime facilities of other programming
languages use the C library to access the underlying operating system.

In GNU/Linux systems, the C library works with the Linux kernel to
implement the operating system behavior seen by user applications.
In GNU/Hurd systems, it works with a microkernel and Hurd servers.

The GNU C Library implements much of the POSIX.1 functionality in the
GNU/Hurd system, using configurations i[4567]86-*-gnu.

When working with Linux kernels, this version of the GNU C Library
requires Linux kernel version 3.2 or later.

Also note that the shared version of the libgcc_s library must be
installed for the pthread library to work correctly.

The GNU C Library supports these configurations for using Linux kernels:

	aarch64*-*-linux-gnu
	alpha*-*-linux-gnu
	arc*-*-linux-gnu
	arm-*-linux-gnueabi
	csky-*-linux-gnuabiv2
	hppa-*-linux-gnu
	i[4567]86-*-linux-gnu
	x86_64-*-linux-gnu	Can build either x86_64 or x32
	ia64-*-linux-gnu
	m68k-*-linux-gnu
	microblaze*-*-linux-gnu
	mips-*-linux-gnu
	mips64-*-linux-gnu
	powerpc-*-linux-gnu	Hardware or software floating point, BE only.
	powerpc64*-*-linux-gnu	Big-endian and little-endian.
	s390-*-linux-gnu
	s390x-*-linux-gnu
	riscv32-*-linux-gnu
	riscv64-*-linux-gnu
	sh[34]-*-linux-gnu
	sparc*-*-linux-gnu
	sparc64*-*-linux-gnu

If you are interested in doing a port, please contact the glibc
maintainers; see https://www.gnu.org/software/libc/ for more
information.

See the file INSTALL to find out how to configure, build, and install
the GNU C Library.  You might also consider reading the WWW pages for
the C library at https://www.gnu.org/software/libc/.

The GNU C Library is (almost) completely documented by the Texinfo manual
found in the `manual/' subdirectory.  The manual is still being updated
and contains some known errors and omissions; we regret that we do not
have the resources to work on the manual as much as we would like.  For
corrections to the manual, please file a bug in the `manual' component,
following the bug-reporting instructions below.  Please be sure to check
the manual in the current development sources to see if your problem has
already been corrected.

Please see https://www.gnu.org/software/libc/bugs.html for bug reporting
information.  We are now using the Bugzilla system to track all bug reports.
This web page gives detailed information on how to report bugs properly.

The GNU C Library is free software.  See the file COPYING.LIB for copying
conditions, and LICENSES for notices about a few contributions that require
these additional notices to be distributed.  License copyright years may be
listed using range notation, e.g., 1996-2015, indicating that every year in
the range, inclusive, is a copyrightable year that would otherwise be listed
individually.

############################################################################

Why I forked this
=================

This would have all the important C and C++ libraries I need for Platypus OS 😅

# Autoconf requirements
# Initialize, but use more options. Mote parameters brackets and whitespace.
AC_INIT([hello], [0.01], [dwheeler@dwheeler.com],
        [hello], [http://www.dwheeler.com/])
# Force autoconf to be at least this version number:
AC_PREREQ([2.68])
# Safety check - list a source file that wouldn't be in other directories:
AC_CONFIG_SRCDIR([src/hello.c])
# Put configuration results here, so we can easily #include them:
AC_CONFIG_HEADERS([config.h])
# Put autotools auxiliary files in a subdir, so theydon't clutter top dir:
AC_CONFIG_AUX_DIR([build-aux])
AC_CONFIG_MACRO_DIR([m4])

# Enable "automake" to simply creating makefiles:
AM_INIT_AUTOMAKE([1.11 subdir-objects -Wall -Werror])
AC_CONFIG_FILES([Makefile])

# Look for a C compiler
AC_PROG_CC
AC_PROG_CC_C_O

# Perhaps check for: (more) programs, libraries, header files, types,
# structures, compiler characteristics, library functions, system services.

# Do final output
AC_OUTPUT

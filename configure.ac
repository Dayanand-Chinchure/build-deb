#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([1.0])
AC_INIT([gofer], [1.0], [dchinchure@gmail.com])
AM_INIT_AUTOMAKE([gofer], [1.0])
AC_CONFIG_SRCDIR([config.h.in])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CC
AC_PROG_INSTALL
AC_PROG_YACC

# Checks for libraries.
# FIXME: Replace `main' with a function in `-lm':
AC_CHECK_LIB([m], [main])

# Checks for header files.
AC_FUNC_ALLOCA
AC_CHECK_HEADERS([fcntl.h libintl.h malloc.h memory.h sgtty.h stddef.h stdlib.h string.h sys/ioctl.h sys/time.h termio.h termios.h values.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_CHECK_HEADER_STDBOOL
AC_C_INLINE
AC_TYPE_SIZE_T

# Checks for library functions.
AC_FUNC_MALLOC
AC_FUNC_REALLOC
AC_CHECK_FUNCS([isascii sqrt strchr])

AC_CONFIG_FILES([Makefile
                 demos/Expert/Makefile
                 doc/Makefile
                 docs/Makefile
                 docsrc/Makefile
                 scripts/Makefile
                 src/Makefile])
AC_OUTPUT()

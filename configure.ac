# http://www.idryman.org/blog/2016/03/10/autoconf-tutorial-1/
#
# Must init the autoconf setup
# The first parameter is project name
# Second is version number
# Third is bug report address
AC_INIT([autohello], [1.0], [christer.enfors@gmail.com])

# Safety checks in case user overwritten --srcdir
AC_CONFIG_SRCDIR([autohello.c])

# Store the auxiliary build tools (e.g. install-sh, config.sub, config.guess)
# in this dir (build-aux)
AC_CONFIG_AUX_DIR([build-aux])

# Init automake, and specify this program use relaxed structures.
# i.e. this program doesn't follow the GNU coding standards, and doesn't have
# Changelog, COPYING, AUTHORS, INSTALL, README etc. files.
AM_INIT_AUTOMAKE([-Wall -Werror foreign])

# Check for C compiler
AC_PROG_CC
# We can add more checks in this section

# Tells automake to create a Makefile
# See https://www.gnu.org/software/automake/manual/html_node/Requirements.html
AC_CONFIG_FILES([Makefile])

# Generate the output
AC_OUTPUT

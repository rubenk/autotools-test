AC_PREREQ([2.61])
AC_INIT([test], [1.0])

AC_MSG_CHECKING([whether to enable the world])
AC_ARG_ENABLE([world],
  [AS_HELP_STRING([--enable-world],[enable the world @<:@default=no@:>@])],
  [enable_world=$enableval],
  [enable_world=no]
)
AC_MSG_RESULT([$enable_world])

if test "x$enable_world" != "xno"; then
  AC_SUBST([subst], [world])
fi


AC_CONFIG_FILES([test.txt])
AC_OUTPUT

project(nativeresourcestring)

add_library_clr(nativeresourcestring
  STATIC
  resourcestring.cpp
)

_install (TARGETS nativeresourcestring DESTINATION lib)

SET( DEFINE
EXAMPLE_MACRO
)
SET( INCLUDE
common
libconfig
msinttypes
mt19937ar
mysql
pcre
zlib
)
SET( LINK
common
libconfig
msinttypes
mt19937ar
mysql
pcre
zlib
pcre.lib
libmysql.lib
ws2_32.lib
zdll.lib
)

create_project(CONSOLE "${DEFINE}" "${INCLUDE}" "${LINK}")

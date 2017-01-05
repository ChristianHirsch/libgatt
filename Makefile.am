AUTOMAKE_OPTIONS = subdir-objects
ACLOCAL_AMFLAGS = ${ACLOCAL_FLAGS} -I m4

libgatt_la_CFLAGS = $(WARNING_CFLAGS) $(MISC_CFLAGS) @GLIB_CFLAGS@ -Isrc
libgatt_la_LDFLAGS = @GLIB_LIBS@

lib_LTLIBRARIES = libgatt.la
libgatt_la_SOURCES = \
					 attrib/gatt.c \
					 attrib/att.c \
					 attrib/gattrib.c \
					 attrib/utils.c \
					 btio/btio.c \
					 lib/uuid.c \
					 lib/hci.c \
					 lib/sdp.c \
					 lib/bluetooth.c \
					 src/shared/att.c \
					 src/shared/crypto.c \
					 src/shared/io-glib.c \
					 src/shared/util.c \
					 src/shared/queue.c \
					 src/shared/timeout-glib.c \
					 src/log.c

pkginclude_HEADERS = attrib/gatt.h \
					 attrib/gattrib.h \
					 attrib/att.h \
					 lib/bluetooth.h \
					 btio/btio.h
#					 lib/hci.h \
#					 lib/hci_lib.h \
#					 lib/l2cap.h \
#					 src/log.h \
#					 lib/rfcomm.h \
#					 lib/sco.h \
#					 lib/sdp.h \
#					 lib/sdp_lib.h \
#					 lib/uuid.h \
#					 src/shared/util.h

gattlibdir = $(includedir)/gatt/lib
gattlib_HEADERS = lib/bluetooth.h \
					 lib/hci.h \
					 lib/hci_lib.h \
					 lib/l2cap.h \
					 lib/rfcomm.h \
					 lib/sco.h \
					 lib/sdp.h \
					 lib/sdp_lib.h \
					 lib/uuid.h

gattsrcdir = $(includedir)/gatt/src
gattsrc_HEADERS = src/log.h 

gattsrcshareddir = $(includedir)/gatt/src/shared
gattsrcshared_HEADERS = src/shared/crypto.h \
						src/shared/util.h 

gattbtiodir = $(includedir)/gatt/btio
gattbtio_HEADERS = btio/btio.h

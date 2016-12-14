AUTOMAKE_OPTIONS = subdir-objects
ACLOCAL_AMFLAGS = ${ACLOCAL_FLAGS} -I m4

libgatt_la_CFLAGS = $(WARNING_CFLAGS) $(MISC_CFLAGS) @GLIB_CFLAGS@ -Isrc
libgatt_la_LDFLAGS = @GLIB_LIBS@

lib_LTLIBRARIES = libgatt.la
libgatt_la_SOURCES = src/att.c src/gatt.c src/gattrib.c src/btio.c src/uuid.c src/hci.c src/sdp.c src/bluetooth.c

pkginclude_HEADERS = src/att.h  src/bluetooth.h  src/btio.h  src/gatt.h  src/gattrib.h  src/hci.h  src/hci_lib.h  src/l2cap.h  src/log.h  src/rfcomm.h  src/sco.h  src/sdp.h  src/sdp_lib.h  src/uuid.h

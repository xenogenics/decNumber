lib_LTLIBRARIES = libdecNumber.la
# Do not include decCommon.c or decBasic.c.
# These get included into other files using the preprocessor.

EXTRA_DIST = decCommon.c decBasic.c ICU-license.html

libdecNumber_la_SOURCES = decContext.c \
			  decDouble.c \
			  decimal128.c \
			  decimal32.c \
			  decimal64.c \
			  decNumber.c \
			  decPacked.c \
			  decQuad.c \
			  decSingle.c

include_HEADERS = decContext.h \
			cdecfloat \
			cdecmath \
			decimal \
			declimits \
		  decDouble.h \
		  decDPD.h \
		  decimal128.h \
		  decimal32.h \
		  decimal64.h \
		  decNumber.h \
		  decNumberLocal.h \
		  decPacked.h \
		  decQuad.h \
		  decSingle.h

# Libtool numbering: current:revision:age
# SEMVER: (current - age).age.revision

libdecNumber_la_LDFLAGS = -version-info 71:0:68

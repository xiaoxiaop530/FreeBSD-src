# $FreeBSD$

TESTSRC=	${SRCTOP}/contrib/netbsd-tests/lib/libpthread/dlopen/dso

SHLIB=		h_pthread_dlopen
SHLIB_MAJOR=    1
SHLIB_NAME=	h_pthread_dlopen.so.${SHLIB_MAJOR}
SRCS=		h_pthread_dlopen.c

DPADD+=		${LIBPTHREAD}
LDADD+=		-lpthread

LIBDIR=         ${TESTSBASE}/lib/libthr/dlopen

.include <netbsd-tests.test.mk>

.include <bsd.lib.mk>

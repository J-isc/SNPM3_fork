# Makefile for adm_Scheduler (ADM_SCHED)
PROG=	adm_sched
SRCS=	main.c

DPADD+=	${LIBSYS} ${LIBTIMERS}
LDADD+=	-lsys -ltimers

CPPFLAGS.main.c+=	-I${NETBSDSRCDIR}/minix

.include <minix.service.mk>

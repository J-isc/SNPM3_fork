.include <bsd.own.mk>

SUBDIR+=	ds input pm rs sched vfs vm adm_sched sched_rr sched_fcfs

.if ${MKIMAGEONLY} == "no"
SUBDIR+=	ipc is devman
.endif

.include <bsd.subdir.mk>

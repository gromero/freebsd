# $FreeBSD$

.include <src.opts.mk>

SUBDIR=	cache
SUBDIR+=concat
.if ${MK_OPENSSL} != "no"
SUBDIR+=eli
.endif
SUBDIR+=journal
SUBDIR+=label
SUBDIR+=mirror
SUBDIR+=mountver
SUBDIR+=multipath
SUBDIR+=nop
SUBDIR+=part
SUBDIR+=raid
SUBDIR+=raid3
SUBDIR+=sched
SUBDIR+=shsec
SUBDIR+=stripe
SUBDIR+=virstor

.include <bsd.subdir.mk>

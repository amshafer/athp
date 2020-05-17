# $FreeBSD$

KMOD=	athp_QCA9377_hw1.0_board-2.bin
FIRMWS=	athp_QCA9377_hw1.0_board-2.bin:athp_QCA9377_hw1.0_board-2.bin:1

CLEANFILES=	board.bin

athp_QCA9377_hw1.0_board-2.bin: ${.CURDIR}/../../../contrib/dev/athp/QCA9377_hw1.0/board-2.bin
	cp ${.CURDIR}/../../../contrib/dev/athp/QCA9377_hw1.0/board-2.bin ${.TARGET}

.include <bsd.kmod.mk>

# $FreeBSD$

KMOD=	athp_QCA9377_hw1.0_firmware-6.bin
FIRMWS=	athp_QCA9377_hw1.0_firmware-6.bin:athp_QCA9377_hw1.0_firmware-6.bin:1

CLEANFILES=	board.bin

athp_QCA9377_hw1.0_firmware-6.bin: ${.CURDIR}/../../../contrib/dev/athp/QCA9377_hw1.0/firmware-6.bin
	cp ${.CURDIR}/../../../contrib/dev/athp/QCA9377_hw1.0/firmware-6.bin ${.TARGET}

.include <bsd.kmod.mk>

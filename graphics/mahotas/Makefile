# Created by: Pedro Garcia Freitas <sawp@sawp.com.br>
# $FreeBSD$

PORTNAME=	mahotas
PORTVERSION=	1.4.5
CATEGORIES=	graphics python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	sawp@sawp.com.br
COMMENT=	Computer vision and image processing library for Python

BUILD_DEPENDS=	${PYNUMPY}
LIB_DEPENDS=	libfreeimage.so:graphics/freeimage

USE_GCC=	yes
USES=		python
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>

# New ports collection makefile for: ghostbsd wallpapers
# Date created:        17 may 2015
# Whom:                angelescuo@yahoo.com
#
# $FreeBSD$
#

PORTNAME=	ghostbsd-wallpapers
PORTVERSION=	19.02
CATEGORIES=	x11-themes

MAINTAINER=	ericturgeon@ghostbsd.org
COMMENT=	GhostBSD 18 wallpaper colection

LICENSE=	BSD

USE_GITHUB=	yes
GH_ACCOUNT=	GhostBSD

NO_BUILD=	yes

do-install:
	${MKDIR} ${STAGEDIR}${PREFIX}/share/backgrounds/ghostbsd
	${CP} -PR ${WRKSRC}/*.jpg ${STAGEDIR}${PREFIX}/share/backgrounds/ghostbsd
	${CP} -PR ${WRKSRC}/*.png ${STAGEDIR}${PREFIX}/share/backgrounds/ghostbsd
	${MKDIR} ${STAGEDIR}${PREFIX}/share/mate-background-properties
	${CP} -PR ${WRKSRC}/ghostbsd.xml ${STAGEDIR}${PREFIX}/share/mate-background-properties/ghostbsd.xml
	${MKDIR} ${STAGEDIR}${PREFIX}/share/gnome-background-properties
	${CP} -PR ${WRKSRC}/ghostbsd.xml ${STAGEDIR}${PREFIX}/share/gnome-background-properties/ghostbsd.xml
.include <bsd.port.mk>

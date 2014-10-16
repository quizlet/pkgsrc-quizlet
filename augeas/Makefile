# $NetBSD$

DISTNAME=	augeas-1.2.0
CATEGORIES=	devel
MASTER_SITES=	http://download.augeas.net/

MAINTAINER=	infrastructure@quizlet.com
HOMEPAGE=	http://download.augeas.net/
COMMENT=	Configuration editing tool
LICENSE=	gnu-lgpl-v2

GNU_CONFIGURE=	yes
USE_TOOLS+=	pkg-config

PKGCONFIG_OVERRIDE+=	augeas.pc.in


.include "../../textproc/libxml2/buildlink3.mk"
.include "../../mk/bsd.pkg.mk"

# $NetBSD: Makefile,v 1.6 2020/09/03 15:46:06 wiz Exp $

DISTNAME=	configobj-5.0.6
PKGNAME=	${PYPKGPREFIX}-${DISTNAME}
PKGREVISION=	2
CATEGORIES=	devel python
MASTER_SITES=	${MASTER_SITE_PYPI:=c/configobj/}

MAINTAINER=	kamelderouiche@yahoo.com
HOMEPAGE=	https://github.com/DiffSK/configobj
COMMENT=	Config file reading, writing and validation
LICENSE=	modified-bsd

DEPENDS+=	${PYPKGPREFIX}-six-[0-9]*:../../lang/py-six

USE_LANGUAGES=	# none

.include "../../lang/python/distutils.mk"
.include "../../mk/bsd.pkg.mk"

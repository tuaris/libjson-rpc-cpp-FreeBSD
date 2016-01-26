# Created by: Daniel Morante <daniel@morante.net>
# $FreeBSD$

PORTNAME=	libjson-rpc-cpp
PORTVERSION=	0.6.0
DISTVERSIONPREFIX=	v
CATEGORIES=	devel

MAINTAINER=	daniel@morante.net
COMMENT=	 C++ framework for json-rpc (json remote procedure call)

LICENSE=	MIT

LIB_DEPENDS=	libboost_python.so:${PORTSDIR}/devel/boost-python-libs \
				libjsoncpp.so:${PORTSDIR}/devel/jsoncpp \
				libcurl.so:${PORTSDIR}/ftp/curl \
				libmicrohttpd.so:${PORTSDIR}/www/libmicrohttpd
				
BUILD_DEPENDS=	${LOCALBASE}/lib/libargtable2.so:${PORTSDIR}/devel/argtable

USE_GITHUB=	yes
GH_ACCOUNT=	cinemast

USES=		cmake
USE_LDCONFIG=	yes

.include <bsd.port.mk>

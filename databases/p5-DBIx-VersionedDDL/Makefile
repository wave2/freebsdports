# New ports collection makefile for:	p5-DBIx-VersionedDDL
# Date created:			30 December 2009
# Whom:				alan
#
# $FreeBSD: ports/databases/p5-DBIx-VersionedDDL/Makefile,v 1.6 2012/01/29 23:11:55 swills Exp $
#

PORTNAME=	DBIx-VersionedDDL
PORTVERSION=	0.16
PORTREVISION=	1
CATEGORIES=	databases perl5
MASTER_SITES=	CPAN
PKGNAMEPREFIX=	p5-

MAINTAINER=	Alan@Wave2.org
COMMENT=	Upgrade and downgrade database schemas to a specified version

BUILD_DEPENDS=	p5-DBD-SQLite>=1.31:${PORTSDIR}/databases/p5-DBD-SQLite \
		p5-Moose>=1.21:${PORTSDIR}/devel/p5-Moose \
		p5-Text-CSV>=1.20:${PORTSDIR}/textproc/p5-Text-CSV \
		p5-MooseX-Attribute-ENV>=0.01:${PORTSDIR}/devel/p5-MooseX-Attribute-ENV \
		p5-MooseX-Object-Pluggable>=0:${PORTSDIR}/devel/p5-MooseX-Object-Pluggable
RUN_DEPENDS=	p5-DBD-SQLite>=1.31:${PORTSDIR}/databases/p5-DBD-SQLite \
		p5-Moose>=1.21:${PORTSDIR}/devel/p5-Moose \
		p5-Text-CSV>=1.20:${PORTSDIR}/textproc/p5-Text-CSV \
		p5-MooseX-Attribute-ENV>=0.01:${PORTSDIR}/devel/p5-MooseX-Attribute-ENV \
		p5-MooseX-Object-Pluggable>=0:${PORTSDIR}/devel/p5-MooseX-Object-Pluggable

PERL_CONFIGURE=	yes

MAN1=	migrate_schema.1
MAN3=	DBIx::VersionedDDL.3 \
	DBIx::VersionedDDL::Plugin::DefaultScriptProcessor.3

.include <bsd.port.mk>

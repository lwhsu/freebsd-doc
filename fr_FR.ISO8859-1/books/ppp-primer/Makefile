#
#    The FreeBSD Documentation Project
#    The FreeBSD French Documentation Project
#
#    Compilation du Manuel PPP
#
#
# 
#    $FreeBSD$
#    Original revision: 1.1
#    $Id$
# 
#    Build the PPP PrimerQ
#

MAINTAINER=gioria@FreeBSD.ORG

DOC?= book

FORMATS?= html-split html

INSTALL_COMPRESSED?= gz
INSTALL_ONLY_COMPRESSED?=

# 
# SRCS lists the individual SGML files that make up the document. Changes
# to any of these files will force a rebuild
#

# SGML content
SRCS=  book.sgml 

DOC_PREFIX?= ${.CURDIR}/../../..

.include "${DOC_PREFIX}/share/mk/doc.project.mk"

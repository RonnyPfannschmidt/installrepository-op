PEP: ?
Title: Detached Wh
Version: $Revision$
Last-Modified: $Date$
Author: Ronny Pannschmidt
Status: draft
Content-Type: text/x-rst
Created: 11-Dec-2012
Post-History: 11-Dec-2012, 28-Dec-2012, 28-Jan-2013


Abstract
========

With the displacement of eggs by wheels the Python ecoystem gained
much in terms of sane and comprehensible installation of python.

However it also lost a set of cappabilities that make vendoring necessary,
version pinning missmatches between co-installed software problematic and
created a general need to materealize packages in each environment.

This PEP aims to procide comprehensible mechanism to
allow the system python and virtual environments alike share all files
of  python packages with each other as well as scripts to depend
on very specific versions of those shared packages if needed.

Additionally this mechanism would allow easy reuse of very hard
to create/install system packages
(examples are pygtk as well as distribution-specific tools)

The Package Repository
======================


Installation of Packages
========================


Pinned Scripts
==============



Leightweight Environments
=========================





Copyright
=========

This document has been placed in the public domain.

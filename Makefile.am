## 
##  This file is part of gPHPEdit, a GNOME2 PHP Editor.
##
##  Copyright (C) 2003, 2004, 2005 Andy Jeffries <andy@gphpedit.org>
##
##  This program is free software; you can redistribute it and/or modify
##  it under the terms of the GNU General Public License as published by
##  the Free Software Foundation; either version 2 of the License, or
##  (at your option) any later version.
##
##  This program is distributed in the hope that it will be useful,
##  but WITHOUT ANY WARRANTY; without even the implied warranty of
##  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
##  GNU General Public License for more details.
##
##  You should have received a copy of the GNU General Public License
##  along with this program; if not, write to the Free Software
##  Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA
##

SUBDIRS = \
	data	\
	doc	\
	pixmaps	\
	src \
	po

applicationsdir = $(datadir)/applications
applications_in_files = gphpedit.desktop.in
applications_DATA = $(applications_in_files:.desktop.in=.desktop)

spec_in_files = gphpedit.spec.in

EXTRA_DIST = \
	gphpedit.spec			\
	gphpedit.applications		\
	$(applications_in_files)	\
	$(spec_in_files)		\
	src/gtkscintilla2

#############################################################################
# Makefile for building: qwtplugin
# Generated by qmake (1.06c) (Qt 3.2.1) on: Wed Jul 11 22:40:34 2012
# Project:  qwtplugin.pro
# Template: lib
# Command: $(QMAKE) -t lib -o Makefile qwtplugin
#############################################################################

####### Compiler, tools and options

CC		=	cl
CXX		=	cl
LEX		= flex
YACC		= byacc
CFLAGS	=	-nologo -Zm200 -W3 -MDd -Zi -GX  -DUNICODE -DQT_DLL -DQT_PLUGIN -DQT_THREAD_SUPPORT
CXXFLAGS	=	-nologo -Zm200 -W3 -MDd -Zi -GX  -DUNICODE -DQT_DLL -DQT_PLUGIN -DQT_THREAD_SUPPORT
LEXFLAGS	=
YACCFLAGS	=-d
INCPATH	=	 -I"..\include" -I"$(QTDIR)\include" -I"E:\scada\src_v\hmi_designer\qwt-4.2.0\designer" -I"moc\\" -I"C:\Qt\3.2.1NonCommercial\mkspecs\win32-msvc"
LINK	=	link
LFLAGS	=	/NOLOGO /DEBUG /SUBSYSTEM:windows /DLL /LIBPATH:"$(QTDIR)\lib"
LIBS	=	 "qt-mtnc321.lib" "kernel32.lib" "user32.lib" "gdi32.lib" "comdlg32.lib" "advapi32.lib" "shell32.lib" "ole32.lib" "oleaut32.lib" "uuid.lib" "imm32.lib" "winmm.lib" "wsock32.lib" "winspool.lib" "..\lib\qwt.lib"
MOC		=	$(QTDIR)\bin\moc.exe
UIC		=	$(QTDIR)\bin\uic.exe
QMAKE		=	qmake
IDC		=	$(QTDIR)\bin\idc.exe
IDL		=	midl
ZIP		=	zip -r -9
COPY_FILE	=       copy
COPY_DIR	=       copy
DEL_FILE	=       del
DEL_DIR	=       rmdir
MOVE		=       move
CHK_DIR_EXISTS =	if not exist
MKDIR		=	mkdir

####### Files

HEADERS =	qwtplugin.h
SOURCES =	qwtplugin.cpp
OBJECTS =	obj\qwtplugin.obj \
		obj\qmake_image_collection.obj
FORMS =	
UICDECLS =	
UICIMPLS =	
SRCMOC	=	
OBJMOC	=	
DIST	=	
TARGET	=	plugins\designer\qwtplugin.dll

####### Implicit rules

.SUFFIXES: .c .cpp .cc .cxx .C

{moc\}.cpp{obj\}.obj::
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Foobj\ @<<
	$<
<<

{moc\}.cc{obj\}.obj::
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Foobj\ @<<
	$<
<<

{moc\}.cxx{obj\}.obj::
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Foobj\ @<<
	$<
<<

{moc\}.C{obj\}.obj::
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Foobj\ @<<
	$<
<<

{moc\}.c{obj\}.obj::
	$(CC) -c $(CFLAGS) $(INCPATH) -Foobj\ @<<
	$<
<<

{.}.cpp{obj\}.obj::
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Foobj\ @<<
	$<
<<

{.}.cc{obj\}.obj::
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Foobj\ @<<
	$<
<<

{.}.cxx{obj\}.obj::
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Foobj\ @<<
	$<
<<

{.}.C{obj\}.obj::
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Foobj\ @<<
	$<
<<

{.}.c{obj\}.obj::
	$(CC) -c $(CFLAGS) $(INCPATH) -Foobj\ @<<
	$<
<<

####### Build rules

all: Makefile $(TARGET)

$(TARGET):  $(UICDECLS) $(OBJECTS) $(OBJMOC) 
	$(LINK) $(LFLAGS) /OUT:$(TARGET) @<< 
	  $(OBJECTS) $(OBJMOC) $(LIBS)
<<


mocables: $(SRCMOC)
uicables: $(UICIMPLS) $(UICDECLS)

Makefile: qwtplugin.pro  C:\Qt\3.2.1NonCommercial\mkspecs\win32-msvc\qmake.conf 
	$(QMAKE) -t lib -o Makefile qwtplugin
qmake: 
	@$(QMAKE) -t lib -o Makefile qwtplugin

dist:
	$(ZIP) qwtplugin.zip $(SOURCES) $(HEADERS) $(DIST) $(FORMS) E:/scada/src_v/hmi_designer/qwt-4.2.0/designer/qwtplugin  pixmaps/qwtplot.png pixmaps/qwtanalogclock.png pixmaps/qwtcounter.png pixmaps/qwtcompass.png pixmaps/qwtdial.png pixmaps/qwtknob.png pixmaps/qwtpushbutton.png pixmaps/qwtscale.png pixmaps/qwtslider.png pixmaps/qwtthermo.png pixmaps/qwtwheel.png pixmaps/qwtwidget.png

uiclean:
mocclean:
clean: uiclean mocclean
	-$(DEL_FILE) obj\qwtplugin.obj
	-$(DEL_FILE) obj\qmake_image_collection.obj
	-$(DEL_FILE) plugins\designer\qwtplugin.exp
	-$(DEL_FILE) plugins\designer\qwtplugin.pdb
	-$(DEL_FILE) plugins\designer\qwtplugin.ilk
	-$(DEL_FILE) vc*.pdb

	-$(DEL_FILE) qmake_image_collection.cpp


FORCE:

distclean: clean
	-$(DEL_FILE) $(TARGET)

####### Compile

obj\qwtplugin.obj: qwtplugin.cpp qwtplugin.h

obj\qmake_image_collection.obj: qmake_image_collection.cpp

qmake_image_collection.cpp: pixmaps\qwtplot.png \
		pixmaps\qwtanalogclock.png \
		pixmaps\qwtcounter.png \
		pixmaps\qwtcompass.png \
		pixmaps\qwtdial.png \
		pixmaps\qwtknob.png \
		pixmaps\qwtpushbutton.png \
		pixmaps\qwtscale.png \
		pixmaps\qwtslider.png \
		pixmaps\qwtthermo.png \
		pixmaps\qwtwheel.png \
		pixmaps\qwtwidget.png
	$(UIC)  -o qmake_image_collection.cpp -embed qwtplugin -f <<
pixmaps\qwtplot.png pixmaps\qwtanalogclock.png pixmaps\qwtcounter.png pixmaps\qwtcompass.png pixmaps\qwtdial.png pixmaps\qwtknob.png pixmaps\qwtpushbutton.png pixmaps\qwtscale.png pixmaps\qwtslider.png pixmaps\qwtthermo.png pixmaps\qwtwheel.png pixmaps\qwtwidget.png
<<

####### Install

install: all 

uninstall: 


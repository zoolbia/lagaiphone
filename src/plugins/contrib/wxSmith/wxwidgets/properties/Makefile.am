AM_CPPFLAGS = -DWXMAKINGDLL_PROPGRID -DwxPG_USE_WXMODULE=0

INCLUDES = $(WX_CXXFLAGS) \
		-I$(top_srcdir)/src/include \
		-I$(top_srcdir)/src/sdk/wxscintilla/include \
		-I$(top_srcdir)/src/sdk/wxpropgrid/include

noinst_LTLIBRARIES = libwxsmith_wxwidgets_properties.la

libwxsmith_wxwidgets_properties_la_LDFLAGS = -module -version-info 0:1:0 -shared -no-undefined -avoid-version

libwxsmith_wxwidgets_properties_la_LIBADD = ../../../../../sdk/libcodeblocks.la

libwxsmith_wxwidgets_properties_la_SOURCES = \
./wxspositionsizeproperty.cpp \
./wxsfonteditordlg.cpp \
./wxsarraystringcheckeditordlg.cpp \
./wxscolourproperty.cpp \
./wxsstyleproperty.cpp \
./wxsarraystringcheckproperty.cpp \
./wxsfontproperty.cpp \
./wxssizerflagsproperty.cpp \
./wxsfontfaceeditordlg.cpp \
./wxsbitmapiconeditordlg.cpp \
./wxsdimensionproperty.cpp \
./wxsbitmapiconproperty.cpp \
./wxssimplefonteditordlg.cpp \
./wxseditenumproperty.cpp \
./wxsimagelistdlg.cpp \
./wxsimagelistproperty.cpp \
./wxsimageproperty.cpp

sdkdir=$(includedir)/wxsmith/wxwidgets/properties/

sdk_HEADERS = \
./wxsdimensionproperty.h \
./wxsbitmapiconproperty.h \
./wxsarraystringcheckeditordlg.h \
./wxsfonteditordlg.h \
./wxspositionsizeproperty.h \
./wxsstyleproperty.h \
./wxscolourproperty.h \
./wxsarraystringcheckproperty.h \
./wxsfontproperty.h \
./wxssizerflagsproperty.h \
./wxsfontfaceeditordlg.h \
./wxsbitmapiconeditordlg.h \
./wxssimplefonteditordlg.h \
./wxseditenumproperty.h \
./wxsimagelistdlg.h \
./wxsimagelistproperty.h \
./wxsimageproperty.h


AM_CPPFLAGS = -DWXMAKINGDLL_PROPGRID -DwxPG_USE_WXMODULE=0

INCLUDES = $(WX_CXXFLAGS) \
		-I$(top_srcdir)/src/include \
		-I$(top_srcdir)/src/plugins/contrib/wxSmith \
		-I$(top_srcdir)/src/sdk/wxpropgrid/include \
		-I$(top_srcdir)/src/plugins/contrib/wxSmithContribItems/wxchart/wxchart-1.0/include


wxsmithcontribitemsdir=$(libdir)/wxSmithContribItems

wxsmithcontribitems_LTLIBRARIES = libwxchartctrl.la

libwxchartctrl_la_LDFLAGS = -version-info 0:1:0

libwxchartctrl_la_LIBADD = $(WX_LIBS)

libwxchartctrl_la_SOURCES = \
./src/axis.cpp \
./src/barchartpoints.cpp \
./src/chart.cpp \
./src/chartwindow.cpp \
./src/legend.cpp \
./src/pie3dchartpoints.cpp \
./src/points.cpp \
./src/xaxiswindow.cpp \
./src/yaxiswindow.cpp \
./src/bar3dchartpoints.cpp \
./src/chartcolors.cpp \
./src/chartctrl.cpp \
./src/chartsizes.cpp \
./src/label.cpp \
./src/legendwindow.cpp \
./src/piechartpoints.cpp \
./src/xaxis.cpp \
./src/yaxis.cpp


sdkdir=$(includedir)/wxSmithContribItems/wxchart/wxchart-1.0/include/wx

sdk_HEADERS = \
./include/wx/axis.h \
./include/wx/bar3dchartpoints.h \
./include/wx/barchartpoints.h \
./include/wx/chartcolors.h \
./include/wx/chartctrl.h \
./include/wx/chartdef.h \
./include/wx/chart.h \
./include/wx/chartpoints.h \
./include/wx/chartpointstypes.h \
./include/wx/chartsizes.h \
./include/wx/charttypes.h \
./include/wx/chartwindow.h \
./include/wx/legend.h \
./include/wx/legendwindow.h \
./include/wx/pie3dchartpoints.h \
./include/wx/piechartpoints.h \
./include/wx/points.h \
./include/wx/xaxis.h \
./include/wx/xaxiswindow.h \
./include/wx/yaxis.h \
./include/wx/yaxiswindow.h


noinst_HEADERS = \
./include/wx/label.h

set(SRC_HARDWARE_RESID
	"${CMAKE_CURRENT_LIST_DIR}/CMakeLists.txt"
	"${CMAKE_CURRENT_LIST_DIR}/envelope.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/envelope.h"
	"${CMAKE_CURRENT_LIST_DIR}/extfilt.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/extfilt.h"
	"${CMAKE_CURRENT_LIST_DIR}/filter.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/filter.h"
	# "${CMAKE_CURRENT_LIST_DIR}/Makefile.am"
	"${CMAKE_CURRENT_LIST_DIR}/pot.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/pot.h"
	"${CMAKE_CURRENT_LIST_DIR}/q.txt"
	"${CMAKE_CURRENT_LIST_DIR}/sid.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/sid.h"
	"${CMAKE_CURRENT_LIST_DIR}/siddefs.h"
	"${CMAKE_CURRENT_LIST_DIR}/spline.h"
	"${CMAKE_CURRENT_LIST_DIR}/version.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/voice.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/voice.h"
	"${CMAKE_CURRENT_LIST_DIR}/wave.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/wave.h"
	"${CMAKE_CURRENT_LIST_DIR}/wave6581_PST.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/wave6581_PS_.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/wave6581_P_T.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/wave6581__ST.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/wave8580_PST.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/wave8580_PS_.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/wave8580_P_T.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/wave8580__ST.cpp"
)
source_group("Sources\\hardware\\reSID" FILES ${SRC_HARDWARE_RESID})
